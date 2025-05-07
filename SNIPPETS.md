# Email Templates

<details>
    <summary><code>emailVerificationLink.js</code></summary>

```js
export const emailVerificationLink = (link) => {
  const html = `
<!DOCTYPE html>
<html lang="en" xmlns:o="urn:schemas-microsoft-com:office:office" xmlns:v="urn:schemas-microsoft-com:vml">

<head>
    <title></title>
    <meta content="text/html; charset=utf-8" http-equiv="Content-Type" />
    <meta content="width=device-width, initial-scale=1.0" name="viewport" />
    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            padding: 0;

        }

        a[x-apple-data-detectors] {
            color: inherit !important;
            text-decoration: inherit !important;
        }

        #MessageViewBody a {
            color: inherit;
            text-decoration: none;
        }

        p {
            line-height: inherit
        }

        .desktop_hide,
        .desktop_hide table {
            mso-hide: all;
            display: none;
            max-height: 0px;
            overflow: hidden;
        }

        .image_block img+div {
            display: none;
        }

        sup,
        sub {
            font-size: 75%;
            line-height: 0;
        }

        @media (max-width:520px) {
            .desktop_hide table.icons-inner {
                display: inline-block !important;
            }

            .icons-inner {
                text-align: center;
            }

            .icons-inner td {
                margin: 0 auto;
            }

            .mobile_hide {
                display: none;
            }

            .row-content {
                width: 100% !important;
            }

            .stack .column {
                width: 100%;
                display: block;
            }

            .mobile_hide {
                min-height: 0;
                max-height: 0;
                max-width: 0;
                overflow: hidden;
                font-size: 0px;
            }

            .desktop_hide,
            .desktop_hide table {
                display: table !important;
                max-height: none !important;
            }
        }
    </style>
</head>

<body class="body"
    style="background-color: #FFFFFF; margin: 0; padding: 0; -webkit-text-size-adjust: none; text-size-adjust: none;">
    <table border="0" cellpadding="0" cellspacing="0" class="nl-container" role="presentation"
        style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; background-color: #FFFFFF;" width="100%">
        <tbody>
            <tr>
                <td>
                    <table align="center" border="0" cellpadding="0" cellspacing="0" class="row row-1"
                        role="presentation"
                        style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; background-color: #f5f5f5; padding:50px 0;"
                        width="100%">
                        <tbody>
                            <tr>
                                <td>
                                    <table align="center" border="0" cellpadding="0" cellspacing="0"
                                        class="row-content stack" role="presentation"
                                        style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; background-color: #ffffff; color: #000000; width: 500px; margin: 0 auto;"
                                        width="500">
                                        <tbody>
                                            <tr>
                                                <td class="column column-1"
                                                    style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; font-weight: 400; text-align: left; padding-bottom: 20px; padding-top: 15px; vertical-align: top; border-top: 0px; border-right: 0px; border-bottom: 0px; border-left: 0px;"
                                                    width="100%">
                                                    <table border="0" cellpadding="0" cellspacing="0"
                                                        class="image_block block-1" role="presentation"
                                                        style="mso-table-lspace: 0pt; mso-table-rspace: 0pt;"
                                                        width="100%">
                                                        <tr>
                                                            <td class="pad"
                                                                style="padding-bottom:5px;padding-left:5px;padding-right:5px;width:100%;">
                                                                <div align="center" class="alignment"
                                                                    style="line-height:10px">
                                                                    <div style="max-width: 250px;"><img
                                                                            alt="reset-password" height="auto"
                                                                            src="https://res.cloudinary.com/do7xdfl3y/image/upload/v1737487850/next-ecommerce/rb_27348_hfzgxd.png"
                                                                            style="display: block; height: auto; border: 0; width: 100%;"
                                                                            title="reset-password" width="250" /></div>
                                                                </div>
                                                            </td>
                                                        </tr>
                                                    </table>
                                                    <table border="0" cellpadding="0" cellspacing="0"
                                                        class="heading_block block-2" role="presentation"
                                                        style="mso-table-lspace: 0pt; mso-table-rspace: 0pt;"
                                                        width="100%">
                                                        <tr>
                                                            <td class="pad" style="text-align:center;width:100%;">
                                                                <h1
                                                                    style="margin: 0; color: #393d47; direction: ltr; font-family: Tahoma, Verdana, Segoe, sans-serif; font-size: 25px; font-weight: normal; letter-spacing: normal; line-height: 120%; text-align: center; margin-top: 0; margin-bottom: 0; mso-line-height-alt: 30px;">
                                                                    <strong>Email Verification</strong>
                                                                </h1>
                                                            </td>
                                                        </tr>
                                                    </table>
                                                    <table border="0" cellpadding="10" cellspacing="0"
                                                        class="paragraph_block block-3" role="presentation"
                                                        style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; word-break: break-word;"
                                                        width="100%">
                                                        <tr>
                                                            <td class="pad">
                                                                <div
                                                                    style="color:#393d47;font-family:Tahoma,Verdana,Segoe,sans-serif;font-size:14px;line-height:150%;text-align:center;mso-line-height-alt:21px;">
                                                                    <p style="margin: 0; word-break: break-word;">We
                                                                        received a request to verify your identity. Use
                                                                        the following link to
                                                                        complete the verification process:</p>
                                                                </div>
                                                            </td>
                                                        </tr>
                                                    </table>
                                                    <table border="0" cellpadding="10" cellspacing="0"
                                                        class="heading_block block-4" role="presentation"
                                                        style="mso-table-lspace: 0pt; mso-table-rspace: 0pt;"
                                                        width="100%">
                                                        <tr>
                                                            <td class="pad">
                                                                <h4
                                                                    style="margin: 0; color: #7747FF; direction: ltr; font-family: Arial, Helvetica Neue, Helvetica, sans-serif; font-size: 20px; font-weight: 700; letter-spacing: normal; line-height: 120%; text-align: center; margin-top: 0; margin-bottom: 0; mso-line-height-alt: 45.6px;">

                                                                    <a href="${link}"
                                                                        style="background-color: #7747FF;color:white;padding:10px 30px;text-decoration: none; border-radius: 50px;">Verify</a>
                                                                </h4>
                                                                
                                                            </td>
                                                        </tr>
                                                    </table>
                                                    <table border="0" cellpadding="10" cellspacing="0"
                                                        class="paragraph_block block-3" role="presentation"
                                                        style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; word-break: break-word;"
                                                        width="100%">
                                                        <tr>
                                                            <td class="pad">
                                                                <div
                                                                    style="color:#393d47;font-family:Tahoma,Verdana,Segoe,sans-serif;font-size:14px;line-height:150%;text-align:center;mso-line-height-alt:21px;">
                                                                    <p style="margin: 0; word-break: break-word;">If the button above doesn’t work, you can copy and
                                                                        paste the following link into your browser:</p>
                                                                      
                                                                        <a href="${link}">${link}</a>
                                                                </div>
                                                            </td>
                                                        </tr>
                                                    </table>
                                                    <table border="0" cellpadding="0" cellspacing="0"
                                                        class="paragraph_block block-5" role="presentation"
                                                        style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; word-break: break-word;"
                                                        width="100%">
                                                        <tr>
                                                            <td class="pad"
                                                                style="padding-bottom:5px;padding-left:10px;padding-right:10px;padding-top:10px;">
                                                                <div
                                                                    style="color:#393d47;font-family:Tahoma,Verdana,Segoe,sans-serif;font-size:13px;line-height:150%;text-align:center;mso-line-height-alt:19.5px;">
                                                                    <p style="margin: 10px;"><strong>Note:</strong> This link will expire in 1 hours. If you did not create an account, you can safely ignore this email.</p>
                                                                         
                                                                    <p style="margin: 0;">Thank you,<br />
                                                                        <a href="https://www.youtube.com/@developergoswami"
                                                                            target="_blank">Developer
                                                                            Goswami</a>
                                                                    </p>
                                                                </div>
                                                            </td>
                                                        </tr>
                                                    </table>
                                                </td>
                                            </tr>
                                        </tbody>
                                    </table>
                                </td>
                            </tr>
                        </tbody>
                    </table>
                </td>
            </tr>
        </tbody>
    </table>
</body>

</html>

      `;

  return html;
};
```

</details>

<details>
    <summary><code>orderNotification.js</code></summary>

```js
export const orderNotification = (data) => {
  const html = `
        <!DOCTYPE html>
  <html lang="en-US" xmlns:o="urn:schemas-microsoft-com:office:office" xmlns:v="urn:schemas-microsoft-com:vml">
<head>
	<title></title>
	<meta content="text/html; charset=utf-8" http-equiv="Content-Type" />
	<meta content="width=device-width, initial-scale=1.0" name="viewport" />
	<style>
		* {
			box-sizing: border-box;
		}

		body {
			margin: 0;
			padding: 0;
		}

		a[x-apple-data-detectors] {
			color: inherit !important;
			text-decoration: inherit !important;
		}

		#MessageViewBody a {
			color: inherit;
			text-decoration: none;
		}

		p {
			line-height: inherit
		}

		.desktop_hide,
		.desktop_hide table {
			mso-hide: all;
			display: none;
			max-height: 0px;
			overflow: hidden;
		}

		.image_block img+div {
			display: none;
		}

		sup,
		sub {
			font-size: 75%;
			line-height: 0;
		}

		.row-4 .column-1 .block-3 .button:hover {
			background-color: #000000 !important;
			border-bottom: 0 solid transparent !important;
			border-left: 0 solid transparent !important;
			border-right: 0px solid transparent !important;
			border-top: 0 solid transparent !important;
			color: #ffffff !important;
		}

		@media (max-width:700px) {

			.desktop_hide table.icons-inner,
			.row-5 .column-2 .block-1.social_block .alignment table,
			.social_block.desktop_hide .social-table {
				display: inline-block !important;
			}

			.icons-inner {
				text-align: center;
			}

			.icons-inner td {
				margin: 0 auto;
			}

			.mobile_hide {
				display: none;
			}

			.row-content {
				width: 100% !important;
			}

			.stack .column {
				width: 100%;
				display: block;
			}

			.mobile_hide {
				min-height: 0;
				max-height: 0;
				max-width: 0;
				overflow: hidden;
				font-size: 0px;
			}

			.desktop_hide,
			.desktop_hide table {
				display: table !important;
				max-height: none !important;
			}

			.row-3 .column-1 .block-2.paragraph_block td.pad>div,
			.row-3 .column-3 .block-1.paragraph_block td.pad>div {
				font-size: 10px !important;
			}

			.row-3 .column-1 .block-2.paragraph_block td.pad {
				padding: 10px !important;
			}

			.row-3 .column-2 .block-1.divider_block td.pad,
			.row-3 .column-4 .block-1.divider_block td.pad {
				padding: 30px 10px 10px !important;
			}

			.row-3 .column-2 .block-1.divider_block .alignment table,
			.row-3 .column-4 .block-1.divider_block .alignment table {
				display: inline-table;
			}

			.row-2 .column-1 .block-1.heading_block h1 {
				font-size: 30px !important;
			}

			.row-3 .column-3 .block-1.paragraph_block td.pad,
			.row-3 .column-5 .block-1.paragraph_block td.pad {
				padding: 25px 0 0 !important;
			}

			.row-3 .column-5 .block-1.paragraph_block td.pad>div {
				text-align: center !important;
				font-size: 10px !important;
			}

			.row-5 .column-1 .block-1.paragraph_block td.pad>div {
				text-align: center !important;
				font-size: 11px !important;
			}

			.row-5 .column-2 .block-1.social_block .alignment {
				text-align: center !important;
			}

			.row-7 .column-1 .block-1.paragraph_block td.pad>div,
			.row-7 .column-2 .block-1.paragraph_block td.pad>div,
			.row-7 .column-3 .block-1.paragraph_block td.pad>div {
				font-size: 11px !important;
			}

			.row-2 .row-content {
				padding: 30px !important;
			}

			.row-4 .row-content {
				padding: 0 30px 30px !important;
			}

			.row-5 .row-content {
				padding: 20px !important;
			}

			.row-6 .row-content {
				padding: 5px 30px !important;
			}

			.row-3 .column-1 {
				padding: 10px 0 5px 5px !important;
			}

			.row-3 .column-5 {
				padding: 5px 10px 5px 0 !important;
			}

			.row-5 .column-2 {
				padding: 20px 0 0 !important;
			}
		}
	</style>

</head>

<body class="body"
	style="background-color: #ffffff; margin: 0; padding: 0; -webkit-text-size-adjust: none; text-size-adjust: none;">
	<table border="0" cellpadding="0" cellspacing="0" class="nl-container" role="presentation"
		style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; background-color: #ffffff;" width="100%">
		<tbody>
			<tr>
				<td>
					<table align="center" border="0" cellpadding="0" cellspacing="0" class="row row-1"
						role="presentation" style="mso-table-lspace: 0pt; mso-table-rspace: 0pt;" width="100%">
						<tbody>
							<tr>
								<td>
									<table align="center" border="0" cellpadding="0" cellspacing="0"
										class="row-content stack" role="presentation"
										style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; background-color: #f7f1ed; border-radius: 0 0 20px 20px; color: #000000; width: 680px; margin: 0 auto;"
										width="680">
										<tbody>
											<tr>
												<td class="column column-1"
													style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; font-weight: 400; text-align: left; padding-bottom: 5px; vertical-align: top;"
													width="100%">
													<table border="0" cellpadding="0" cellspacing="0"
														class="image_block block-1" role="presentation"
														style="mso-table-lspace: 0pt; mso-table-rspace: 0pt;"
														width="100%">
														<tr>
															<td class="pad"
																style="width:100%;padding-right:0px;padding-left:0px;">
																<div align="center" class="alignment">
																	<div style="max-width: 248px;"><img alt="Logo"
																			height="auto" src="https://res.cloudinary.com/do7xdfl3y/image/upload/v1746551738/next-ecommerce/logo-black_bxt60d.png"
																			style="display: block; height: auto; border: 0; width: 100%;"
																			title="Logo" width="248" /></div>
																</div>
															</td>
														</tr>
													</table>
												</td>
											</tr>
										</tbody>
									</table>
								</td>
							</tr>
						</tbody>
					</table>
					<table align="center" border="0" cellpadding="0" cellspacing="0" class="row row-2"
						role="presentation" style="mso-table-lspace: 0pt; mso-table-rspace: 0pt;" width="100%">
						<tbody>
							<tr>
								<td>
									<table align="center" border="0" cellpadding="0" cellspacing="0"
										class="row-content stack" role="presentation"
										style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-radius: 0; color: #000000; padding: 30px 60px 20px; width: 680px; margin: 0 auto;"
										width="680">
										<tbody>
											<tr>
												<td class="column column-1"
													style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; font-weight: 400; text-align: left; padding-bottom: 5px; padding-top: 5px; vertical-align: top;"
													width="100%">
													<table border="0" cellpadding="10" cellspacing="0"
														class="heading_block block-1" role="presentation"
														style="mso-table-lspace: 0pt; mso-table-rspace: 0pt;"
														width="100%">
														<tr>
															<td class="pad">
																<h1
																	style="margin: 0; color: #000000; direction: ltr; font-family: TimesNewRoman, 'Times New Roman', Times, Baskerville, Georgia, serif; font-size: 40px; font-weight: 400; letter-spacing: -2px; line-height: 1.2; text-align: center; margin-top: 0; margin-bottom: 0; mso-line-height-alt: 48px;">
																	<span class="tinyMce-placeholder"
																		style="word-break: break-word;">YOUR ORDER WILL
																		BE SHIPPED SOON!</span>
																</h1>
															</td>
														</tr>
													</table>
												</td>
											</tr>
										</tbody>
									</table>
								</td>
							</tr>
						</tbody>
					</table>
					<table align="center" border="0" cellpadding="0" cellspacing="0" class="row row-3"
						role="presentation" style="mso-table-lspace: 0pt; mso-table-rspace: 0pt;" width="100%">
						<tbody>
							<tr>
								<td>
									<table align="center" border="0" cellpadding="0" cellspacing="0" class="row-content"
										role="presentation"
										style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-radius: 0; color: #000000; width: 680px; margin: 0 auto;"
										width="680">
										<tbody>
											<tr>
												<td class="column column-1"
													style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; font-weight: 400; text-align: left; padding-bottom: 5px; padding-left: 45px; padding-top: 10px; vertical-align: top;"
													width="25%">
													<table border="0" cellpadding="0" cellspacing="0"
														class="image_block block-1" role="presentation"
														style="mso-table-lspace: 0pt; mso-table-rspace: 0pt;"
														width="100%">
														<tr>
															<td class="pad"
																style="width:100%;padding-right:0px;padding-left:0px;">
																<div align="center" class="alignment">
																	<div style="max-width: 13px;"><img alt="Check"
																			height="auto" src="https://res.cloudinary.com/do7xdfl3y/image/upload/v1746551738/next-ecommerce/check-orange_g480te.png"
																			style="display: block; height: auto; border: 0; width: 100%;"
																			title="Check" width="13" /></div>
																</div>
															</td>
														</tr>
													</table>
													<table border="0" cellpadding="0" cellspacing="0"
														class="paragraph_block block-2" role="presentation"
														style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; word-break: break-word;"
														width="100%">
														<tr>
															<td class="pad" style="padding-top:10px;">
																<div
																	style="color:#000000;direction:ltr;font-family:TimesNewRoman, 'Times New Roman', Times, Baskerville, Georgia, serif;font-size:18px;font-weight:700;letter-spacing:0px;line-height:1.2;text-align:center;mso-line-height-alt:22px;">
																	<p style="margin: 0;">Confirmed</p>
																</div>
															</td>
														</tr>
													</table>
												</td>
												<td class="column column-2"
													style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; font-weight: 400; text-align: left; padding-bottom: 5px; padding-top: 5px; vertical-align: top;"
													width="16.666666666666668%">
													<table border="0" cellpadding="0" cellspacing="0"
														class="divider_block block-1" role="presentation"
														style="mso-table-lspace: 0pt; mso-table-rspace: 0pt;"
														width="100%">
														<tr>
															<td class="pad"
																style="padding-bottom:10px;padding-left:10px;padding-right:10px;padding-top:35px;">
																<div align="center" class="alignment">
																	<table border="0" cellpadding="0" cellspacing="0"
																		role="presentation"
																		style="mso-table-lspace: 0pt; mso-table-rspace: 0pt;"
																		width="100%">
																		<tr>
																			<td class="divider_inner"
																				style="font-size: 1px; line-height: 1px; border-top: 2px solid #e1cabf;">
																				<span
																					style="word-break: break-word;"> </span>
																			</td>
																		</tr>
																	</table>
																</div>
															</td>
														</tr>
													</table>
												</td>
												<td class="column column-3"
													style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; font-weight: 400; text-align: left; padding-bottom: 5px; padding-top: 5px; vertical-align: top;"
													width="16.666666666666668%">
													<table border="0" cellpadding="0" cellspacing="0"
														class="paragraph_block block-1" role="presentation"
														style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; word-break: break-word;"
														width="100%">
														<tr>
															<td class="pad" style="padding-top:25px;">
																<div
																	style="color:#e1cabf;direction:ltr;font-family:TimesNewRoman, 'Times New Roman', Times, Baskerville, Georgia, serif;font-size:18px;font-weight:400;letter-spacing:0px;line-height:1.2;text-align:center;mso-line-height-alt:22px;">
																	<p style="margin: 0;">Shipped</p>
																</div>
															</td>
														</tr>
													</table>
												</td>
												<td class="column column-4"
													style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; font-weight: 400; text-align: left; padding-bottom: 5px; padding-top: 5px; vertical-align: top;"
													width="16.666666666666668%">
													<table border="0" cellpadding="0" cellspacing="0"
														class="divider_block block-1" role="presentation"
														style="mso-table-lspace: 0pt; mso-table-rspace: 0pt;"
														width="100%">
														<tr>
															<td class="pad"
																style="padding-bottom:10px;padding-left:10px;padding-right:10px;padding-top:35px;">
																<div align="center" class="alignment">
																	<table border="0" cellpadding="0" cellspacing="0"
																		role="presentation"
																		style="mso-table-lspace: 0pt; mso-table-rspace: 0pt;"
																		width="100%">
																		<tr>
																			<td class="divider_inner"
																				style="font-size: 1px; line-height: 1px; border-top: 2px solid #e1cabf;">
																				<span
																					style="word-break: break-word;"> </span>
																			</td>
																		</tr>
																	</table>
																</div>
															</td>
														</tr>
													</table>
												</td>
												<td class="column column-5"
													style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; font-weight: 400; text-align: left; padding-bottom: 5px; padding-left: 10px; padding-top: 5px; vertical-align: top;"
													width="25%">
													<table border="0" cellpadding="0" cellspacing="0"
														class="paragraph_block block-1" role="presentation"
														style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; word-break: break-word;"
														width="100%">
														<tr>
															<td class="pad" style="padding-left:10px;padding-top:25px;">
																<div
																	style="color:#e1cabf;direction:ltr;font-family:TimesNewRoman, 'Times New Roman', Times, Baskerville, Georgia, serif;font-size:18px;font-weight:400;letter-spacing:0px;line-height:1.2;text-align:left;mso-line-height-alt:22px;">
																	<p style="margin: 0;">Delivered</p>
																</div>
															</td>
														</tr>
													</table>
												</td>
											</tr>
										</tbody>
									</table>
								</td>
							</tr>
						</tbody>
					</table>
					<table align="center" border="0" cellpadding="0" cellspacing="0" class="row row-4"
						role="presentation" style="mso-table-lspace: 0pt; mso-table-rspace: 0pt;" width="100%">
						<tbody>
							<tr>
								<td>
									<table align="center" border="0" cellpadding="0" cellspacing="0"
										class="row-content stack" role="presentation"
										style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-radius: 0; color: #000000; padding-bottom: 60px; padding-left: 60px; padding-right: 60px; width: 680px; margin: 0 auto;"
										width="680">
										<tbody>
											<tr>
												<td class="column column-1"
													style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; font-weight: 400; text-align: left; padding-bottom: 5px; padding-top: 5px; vertical-align: top;"
													width="100%">
													<table border="0" cellpadding="40" cellspacing="0"
														class="image_block block-1" role="presentation"
														style="mso-table-lspace: 0pt; mso-table-rspace: 0pt;"
														width="100%">
														<tr>
															<td class="pad">
																<div align="center" class="alignment">
																	<div style="max-width: 130px;"><img
																			alt="a hand with a star" height="auto"
																			src="https://res.cloudinary.com/do7xdfl3y/image/upload/v1746551738/next-ecommerce/order-conf-icon_ljhxtd.png"
																			style="display: block; height: auto; border: 0; width: 100%;"
																			title="a hand with a star" width="130" />
																	</div>
																</div>
															</td>
														</tr>
													</table>
													<table border="0" cellpadding="0" cellspacing="0"
														class="heading_block block-2" role="presentation"
														style="mso-table-lspace: 0pt; mso-table-rspace: 0pt;"
														width="100%">
														<tr>
															<td class="pad"
																style="padding-bottom:35px;padding-left:10px;padding-right:10px;padding-top:10px;text-align:center;width:100%;">
																<h3
																	style="margin: 0; color: #4400ff; direction: ltr; font-family: TimesNewRoman, 'Times New Roman', Times, Baskerville, Georgia, serif; font-size: 24px; font-weight: 700; letter-spacing: normal; line-height: 1.2; text-align: center; margin-top: 0; margin-bottom: 0; mso-line-height-alt: 29px;">
																	<span class="tinyMce-placeholder"
																		style="word-break: break-word;">Order Id:
																		${data.order_id} </span>
																</h3>
															</td>
														</tr>
													</table>
													<table border="0" cellpadding="0" cellspacing="0"
														class="button_block block-3" role="presentation"
														style="mso-table-lspace: 0pt; mso-table-rspace: 0pt;"
														width="100%">
														<tr>
															<td class="pad" style="text-align:center;">
																<div align="center" class="alignment"><a
																		href="${data.orderDetailsUrl}"
																		style="color:#ffffff;text-decoration:none;"
																		target="_blank"> <span class="button"
																			style="background-color: #9502f5; border-bottom: 0px solid #f65c03; border-left: 0px solid #f65c03; border-radius: 30px; border-right: 0px solid #f65c03; border-top: 0px solid #f65c03; color: #ffffff; display: inline-block; font-family: TimesNewRoman, 'Times New Roman', Times, Baskerville, Georgia, serif; font-size: 16px; font-weight: 700; mso-border-alt: none; padding-bottom: 5px; padding-top: 5px; padding-left: 30px; padding-right: 30px; text-align: center; width: auto; word-break: keep-all; letter-spacing: 1px;"><span
																				style="word-break: break-word; line-height: 32px;">VIEW
																				MY
																				ORDER</span></span> </a>
																</div>
															</td>
														</tr>
													</table>
												</td>
											</tr>
										</tbody>
									</table>
								</td>
							</tr>
						</tbody>
					</table>
					<table align="center" border="0" cellpadding="0" cellspacing="0" class="row row-5"
						role="presentation" style="mso-table-lspace: 0pt; mso-table-rspace: 0pt;" width="100%">
						<tbody>
							<tr>
								<td>
									<table align="center" border="0" cellpadding="0" cellspacing="0"
										class="row-content stack" role="presentation"
										style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; background-color: #000000; border-radius: 20px 20px 0 0; color: #000000; padding-bottom: 20px; padding-left: 60px; padding-top: 20px; width: 680px; margin: 0 auto;"
										width="680">
										<tbody>
											<tr>
												<td class="column column-1"
													style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; font-weight: 400; text-align: left; padding-top: 20px; vertical-align: top;"
													width="58.333333333333336%">
													<table border="0" cellpadding="0" cellspacing="0"
														class="paragraph_block block-1" role="presentation"
														style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; word-break: break-word;"
														width="100%">
														<tr>
															<td class="pad"
																style="padding-bottom:5px;padding-left:10px;padding-right:10px;padding-top:5px;">
																<div
																	style="color:#f7f1ed;direction:ltr;font-family:TimesNewRoman, 'Times New Roman', Times, Baskerville, Georgia, serif;font-size:14px;font-weight:700;letter-spacing:3px;line-height:1.2;text-align:left;mso-line-height-alt:17px;">
																	<p style="margin: 0;">FUEL FOR YOUR INNER GLOW</p>
																</div>
															</td>
														</tr>
													</table>
												</td>
												<td class="column column-2"
													style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; font-weight: 400; text-align: left; padding-right: 50px; padding-top: 20px; vertical-align: top;"
													width="41.666666666666664%">
													<table border="0" cellpadding="0" cellspacing="0"
														class="social_block block-1" role="presentation"
														style="mso-table-lspace: 0pt; mso-table-rspace: 0pt;"
														width="100%">
														<tr>
															<td class="pad"
																style="text-align:right;padding-right:0px;padding-left:0px;">
																<div align="right" class="alignment">
																	<table border="0" cellpadding="0" cellspacing="0"
																		class="social-table" role="presentation"
																		style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; display: inline-block;"
																		width="108px">
																		<tr>
																			<td style="padding:0 0 0 4px;"><a
																					href="https://www.facebook.com/"
																					target="_blank"><img alt="facebook"
																						height="auto"
																						src="https://res.cloudinary.com/do7xdfl3y/image/upload/v1746551738/next-ecommerce/facebook2x_i55n3x.png"
																						style="display: block; height: auto; border: 0;"
																						title="facebook"
																						width="32" /></a></td>
																			<td style="padding:0 0 0 4px;"><a
																					href="https://www.twitter.com/"
																					target="_blank"><img alt="twitter"
																						height="auto"
																						src="https://res.cloudinary.com/do7xdfl3y/image/upload/v1746551738/next-ecommerce/twitter2x_mw4wta.png"
																						style="display: block; height: auto; border: 0;"
																						title="twitter"
																						width="32" /></a></td>
																			<td style="padding:0 0 0 4px;"><a
																					href="https://www.instagram.com/"
																					target="_blank"><img alt="instagram"
																						height="auto"
																						src="https://res.cloudinary.com/do7xdfl3y/image/upload/v1746551738/next-ecommerce/instagram2x_te7lqu.png"
																						style="display: block; height: auto; border: 0;"
																						title="instagram"
																						width="32" /></a></td>
																		</tr>
																	</table>
																</div>
															</td>
														</tr>
													</table>
												</td>
											</tr>
										</tbody>
									</table>
								</td>
							</tr>
						</tbody>
					</table>
					<table align="center" border="0" cellpadding="0" cellspacing="0" class="row row-6"
						role="presentation" style="mso-table-lspace: 0pt; mso-table-rspace: 0pt;" width="100%">
						<tbody>
							<tr>
								<td>
									<table align="center" border="0" cellpadding="0" cellspacing="0"
										class="row-content stack" role="presentation"
										style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; background-color: #000000; border-radius: 0; color: #000000; padding: 5px 60px; width: 680px; margin: 0 auto;"
										width="680">
										<tbody>
											<tr>
												<td class="column column-1"
													style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; font-weight: 400; text-align: left; vertical-align: top;"
													width="100%">
													<table border="0" cellpadding="0" cellspacing="0"
														class="divider_block block-1" role="presentation"
														style="mso-table-lspace: 0pt; mso-table-rspace: 0pt;"
														width="100%">
														<tr>
															<td class="pad"
																style="padding-bottom:10px;padding-top:10px;">
																<div align="center" class="alignment">
																	<table border="0" cellpadding="0" cellspacing="0"
																		role="presentation"
																		style="mso-table-lspace: 0pt; mso-table-rspace: 0pt;"
																		width="100%">
																		<tr>
																			<td class="divider_inner"
																				style="font-size: 1px; line-height: 1px; border-top: 1px solid #3a3a3a;">
																				<span
																					style="word-break: break-word;"> </span>
																			</td>
																		</tr>
																	</table>
																</div>
															</td>
														</tr>
													</table>
													<table border="0" cellpadding="0" cellspacing="0"
														class="paragraph_block block-2" role="presentation"
														style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; word-break: break-word;"
														width="100%">
														<tr>
															<td class="pad"
																style="padding-bottom:20px;padding-top:20px;">
																<div
																	style="color:#ffffff;direction:ltr;font-family:TimesNewRoman, 'Times New Roman', Times, Baskerville, Georgia, serif;font-size:18px;font-weight:400;letter-spacing:0px;line-height:1.2;text-align:left;mso-line-height-alt:22px;">
																	<p style="margin: 0;"><strong>Have a
																			question?</strong> We love curiosity. <a
																			href="contact-us.com" rel="noopener"
																			style="text-decoration: underline; color: #ffffff;"
																			target="_blank">contact us</a></p>
																</div>
															</td>
														</tr>
													</table>
													<table border="0" cellpadding="0" cellspacing="0"
														class="divider_block block-3" role="presentation"
														style="mso-table-lspace: 0pt; mso-table-rspace: 0pt;"
														width="100%">
														<tr>
															<td class="pad"
																style="padding-bottom:10px;padding-top:10px;">
																<div align="center" class="alignment">
																	<table border="0" cellpadding="0" cellspacing="0"
																		role="presentation"
																		style="mso-table-lspace: 0pt; mso-table-rspace: 0pt;"
																		width="100%">
																		<tr>
																			<td class="divider_inner"
																				style="font-size: 1px; line-height: 1px; border-top: 1px solid #3a3a3a;">
																				<span
																					style="word-break: break-word;"> </span>
																			</td>
																		</tr>
																	</table>
																</div>
															</td>
														</tr>
													</table>
													<table border="0" cellpadding="0" cellspacing="0"
														class="paragraph_block block-4" role="presentation"
														style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; word-break: break-word;"
														width="100%">
														<tr>
															<td class="pad"
																style="padding-bottom:5px;padding-top:15px;">
																<div
																	style="color:#ffffff;direction:ltr;font-family:TimesNewRoman, 'Times New Roman', Times, Baskerville, Georgia, serif;font-size:15px;font-weight:400;letter-spacing:0px;line-height:1.2;text-align:left;mso-line-height-alt:18px;">
																	<p style="margin: 0;">How much do you want to hear
																		from us?</p>
																</div>
															</td>
														</tr>
													</table>
												</td>
											</tr>
										</tbody>
									</table>
								</td>
							</tr>
						</tbody>
					</table>
					<table align="center" border="0" cellpadding="0" cellspacing="0" class="row row-7"
						role="presentation" style="mso-table-lspace: 0pt; mso-table-rspace: 0pt;" width="100%">
						<tbody>
							<tr>
								<td>
									<table align="center" border="0" cellpadding="0" cellspacing="0" class="row-content"
										role="presentation"
										style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; background-color: #000000; border-radius: 0; color: #000000; width: 680px; margin: 0 auto;"
										width="680">
										<tbody>
											<tr>
												<td class="column column-1"
													style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; font-weight: 400; text-align: left; padding-bottom: 5px; padding-left: 20px; padding-top: 5px; vertical-align: top;"
													width="33.333333333333336%">
													<table border="0" cellpadding="0" cellspacing="0"
														class="paragraph_block block-1" role="presentation"
														style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; word-break: break-word;"
														width="100%">
														<tr>
															<td class="pad"
																style="padding-bottom:20px;padding-top:15px;">
																<div
																	style="color:#f7f1ed;direction:ltr;font-family:TimesNewRoman, 'Times New Roman', Times, Baskerville, Georgia, serif;font-size:13px;font-weight:400;letter-spacing:0px;line-height:1.2;text-align:center;mso-line-height-alt:16px;">
																	<p style="margin: 0;"><a
																			href="https://www.example.com"
																			rel="noopener"
																			style="text-decoration: underline; color: #f7f1ed;"
																			target="_blank">Give me everything!</a></p>
																</div>
															</td>
														</tr>
													</table>
												</td>
												<td class="column column-2"
													style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; font-weight: 400; text-align: left; padding-bottom: 5px; padding-left: 20px; padding-right: 20px; padding-top: 5px; vertical-align: top;"
													width="33.333333333333336%">
													<table border="0" cellpadding="0" cellspacing="0"
														class="paragraph_block block-1" role="presentation"
														style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; word-break: break-word;"
														width="100%">
														<tr>
															<td class="pad"
																style="padding-bottom:20px;padding-top:15px;">
																<div
																	style="color:#f7f1ed;direction:ltr;font-family:TimesNewRoman, 'Times New Roman', Times, Baskerville, Georgia, serif;font-size:13px;font-weight:400;letter-spacing:0px;line-height:1.2;text-align:center;mso-line-height-alt:16px;">
																	<p style="margin: 0;"><a
																			href="https://www.example.com"
																			rel="noopener"
																			style="text-decoration: underline; color: #f7f1ed;"
																			target="_blank">Just the essentials.</a></p>
																</div>
															</td>
														</tr>
													</table>
												</td>
												<td class="column column-3"
													style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; font-weight: 400; text-align: left; padding-bottom: 20px; padding-right: 20px; padding-top: 5px; vertical-align: top;"
													width="33.333333333333336%">
													<table border="0" cellpadding="0" cellspacing="0"
														class="paragraph_block block-1" role="presentation"
														style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; word-break: break-word;"
														width="100%">
														<tr>
															<td class="pad"
																style="padding-bottom:20px;padding-top:15px;">
																<div
																	style="color:#f7f1ed;direction:ltr;font-family:TimesNewRoman, 'Times New Roman', Times, Baskerville, Georgia, serif;font-size:13px;font-weight:400;letter-spacing:0px;line-height:1.2;text-align:center;mso-line-height-alt:16px;">
																	<p style="margin: 0;"><a
																			href="https://www.example.com"
																			rel="noopener"
																			style="text-decoration: underline; color: #f7f1ed;"
																			target="_blank">Unsubscribe</a></p>
																</div>
															</td>
														</tr>
													</table>
												</td>
											</tr>
										</tbody>
									</table>
								</td>
							</tr>
						</tbody>
					</table>

				</td>
			</tr>
		</tbody>
	</table> 
</body>

</html>
`;

  return html;
};
```

</details>

<details>
    <summary><code>otpEmail.js</code></summary>

```js
export const otpEmail = (otp) => {
  const html = `
<!DOCTYPE html>
<html lang="en" xmlns:o="urn:schemas-microsoft-com:office:office" xmlns:v="urn:schemas-microsoft-com:vml">
<head>
	<title></title>
	<meta content="text/html; charset=utf-8" http-equiv="Content-Type" />
	<meta content="width=device-width, initial-scale=1.0" name="viewport" />
	<style>
		* {
			box-sizing: border-box;
		}

		body {
			margin: 0;
			padding: 0;
			 
		}

		a[x-apple-data-detectors] {
			color: inherit !important;
			text-decoration: inherit !important;
		}

		#MessageViewBody a {
			color: inherit;
			text-decoration: none;
		}

		p {
			line-height: inherit
		}

		.desktop_hide,
		.desktop_hide table {
			mso-hide: all;
			display: none;
			max-height: 0px;
			overflow: hidden;
		}

		.image_block img+div {
			display: none;
		}

		sup,
		sub {
			font-size: 75%;
			line-height: 0;
		}

		@media (max-width:520px) {
			.desktop_hide table.icons-inner {
				display: inline-block !important;
			}

			.icons-inner {
				text-align: center;
			}

			.icons-inner td {
				margin: 0 auto;
			}

			.mobile_hide {
				display: none;
			}

			.row-content {
				width: 100% !important;
			}

			.stack .column {
				width: 100%;
				display: block;
			}

			.mobile_hide {
				min-height: 0;
				max-height: 0;
				max-width: 0;
				overflow: hidden;
				font-size: 0px;
			}

			.desktop_hide,
			.desktop_hide table {
				display: table !important;
				max-height: none !important;
			}
		}
	</style>
</head>

<body class="body"
	style="background-color: #FFFFFF; margin: 0; padding: 0; -webkit-text-size-adjust: none; text-size-adjust: none;">
	<table border="0" cellpadding="0" cellspacing="0" class="nl-container" role="presentation"
		style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; background-color: #FFFFFF;" width="100%">
		<tbody>
			<tr>
				<td>
					<table align="center" border="0" cellpadding="0" cellspacing="0" class="row row-1"
						role="presentation"
						style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; background-color: #f5f5f5;padding:50px 0;" width="100%">
						<tbody>
							<tr>
								<td>
									<table align="center" border="0" cellpadding="0" cellspacing="0"
										class="row-content stack" role="presentation"
										style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; background-color: #ffffff; color: #000000; width: 500px; margin: 0 auto;"
										width="500">
										<tbody>
											<tr>
												<td class="column column-1"
													style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; font-weight: 400; text-align: left; padding-bottom: 20px; padding-top: 15px; vertical-align: top; border-top: 0px; border-right: 0px; border-bottom: 0px; border-left: 0px;"
													width="100%">
													<table border="0" cellpadding="0" cellspacing="0"
														class="image_block block-1" role="presentation"
														style="mso-table-lspace: 0pt; mso-table-rspace: 0pt;"
														width="100%">
														<tr>
															<td class="pad"
																style="padding-bottom:5px;padding-left:5px;padding-right:5px;width:100%;">
																<div align="center" class="alignment"
																	style="line-height:10px">
																	<div style="max-width: 250px;"><img
																			alt="reset-password" height="auto"
																			src="https://res.cloudinary.com/do7xdfl3y/image/upload/v1737487850/next-ecommerce/rb_27348_hfzgxd.png"
																			style="display: block; height: auto; border: 0; width: 100%;"
																			title="reset-password" width="250" /></div>
																</div>
															</td>
														</tr>
													</table>
													<table border="0" cellpadding="0" cellspacing="0"
														class="heading_block block-2" role="presentation"
														style="mso-table-lspace: 0pt; mso-table-rspace: 0pt;"
														width="100%">
														<tr>
															<td class="pad" style="text-align:center;width:100%;">
																<h1
																	style="margin: 0; color: #393d47; direction: ltr; font-family: Tahoma, Verdana, Segoe, sans-serif; font-size: 25px; font-weight: normal; letter-spacing: normal; line-height: 120%; text-align: center; margin-top: 0; margin-bottom: 0; mso-line-height-alt: 30px;">
																	<strong>Email Verification</strong>
																</h1>
															</td>
														</tr>
													</table>
													<table border="0" cellpadding="10" cellspacing="0"
														class="paragraph_block block-3" role="presentation"
														style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; word-break: break-word;"
														width="100%">
														<tr>
															<td class="pad">
																<div
																	style="color:#393d47;font-family:Tahoma,Verdana,Segoe,sans-serif;font-size:14px;line-height:150%;text-align:center;mso-line-height-alt:21px;">
																	<p style="margin: 0; word-break: break-word;">We
																		received a request to verify your identity. Use
																		the following One-Time Password (OTP) to
																		complete the verification process:</p>
																</div>
															</td>
														</tr>
													</table>
													<table border="0" cellpadding="10" cellspacing="0"
														class="heading_block block-4" role="presentation"
														style="mso-table-lspace: 0pt; mso-table-rspace: 0pt;"
														width="100%">
														<tr>
															<td class="pad">
																<h1
																	style="margin: 0; color: #7747FF; direction: ltr; font-family: Arial, Helvetica Neue, Helvetica, sans-serif; font-size: 38px; font-weight: 700; letter-spacing: normal; line-height: 120%; text-align: center; margin-top: 0; margin-bottom: 0; mso-line-height-alt: 45.6px;">
																	<span class="tinyMce-placeholder"
																		style="word-break: break-word;">${otp}</span>
																</h1>
															</td>
														</tr>
													</table>
													<table border="0" cellpadding="0" cellspacing="0"
														class="paragraph_block block-5" role="presentation"
														style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; word-break: break-word;"
														width="100%">
														<tr>
															<td class="pad"
																style="padding-bottom:5px;padding-left:10px;padding-right:10px;padding-top:10px;">
																<div
																	style="color:#393d47;font-family:Tahoma,Verdana,Segoe,sans-serif;font-size:13px;line-height:150%;text-align:center;mso-line-height-alt:19.5px;">
																	<p style="margin: 0;"><strong>Note:</strong> This
																		OTP is valid for 10 minutes. Do not share it
																		with anyone.</p>
																	<p style="margin: 0;">If you did not request this,
																		please ignore this message.</p>
																	<p style="margin: 0;">Thank you,<br />
                                                                     <a href="https://www.youtube.com/@developergoswami" target="_blank">Developer
																		Goswami</a>
                                                                    </p>
																</div>
															</td>
														</tr>
													</table>
												</td>
											</tr>
										</tbody>
									</table>
								</td>
							</tr>
						</tbody>
					</table>
				</td>
			</tr>
		</tbody>
	</table>
</body>
</html>

      `;

  return html;
};
```

</details>

# lib Folder

<details>
    <summary><code>materialTheme.js</code></summary>

```js
import { createTheme } from "@mui/material";
import { Assistant } from "next/font/google";
const assistantFont = Assistant({
  weight: ["400", "500", "600", "700", "800"],
  display: "swap",
  subsets: ["latin"],
});

export const lightTheme = createTheme({
  colorSchemes: {
    light: true,
  },
  palette: {
    mode: "light",
    common: {
      black: "#030712",
      white: "#fff",
    },
    primary: {
      main: "#8e51ff",
    },
    secondary: {
      main: "#8e51ff",
      light: "#f8fafc",
    },
    background: {
      paper: "#ffffff",
      default: "#ffffff",
    },
    text: {
      primary: "#030712",
      secondary: "#6B7280",
    },
    success: {
      main: "#22c55e",
      light: "#4caf50",
      dark: "#1b5e20",
      contrastText: "#fff",
    },
  },
  typography: {
    fontFamily: assistantFont.style.fontFamily,
  },
  shadows: {
    0: "none",
    1: "0px 2px 1px -1px rgba(0,0,0,0.150),0px 1px 1px 0px rgba(0,0,0,0.150),0px 1px 3px 0px rgba(0,0,0,0.150)",
    2: "none",
    8: "0 5px 5px rgba(0, 0,0,0.15)",
  },
});

export const darkTheme = createTheme({
  colorSchemes: {
    dark: true,
  },
  palette: {
    mode: "dark",
    common: {
      black: "#030712",
      white: "#fff",
    },
    primary: {
      main: "#8e51ff",
    },
    background: {
      paper: "#0b0a10",
      default: "#0b0a10",
    },
    text: {
      primary: "#d4d4d4",
      secondary: "#9ca3af",
    },
    action: {
      active: "#9ca3af",
    },
  },
  typography: {
    fontFamily: assistantFont.style.fontFamily,
  },
  shadows: {
    0: "none",
    1: "0px 2px 1px -1px rgba(0,0,0,0.2),0px 1px 1px 0px rgba(0,0,0,0.14),0px 1px 3px 0px rgba(0,0,0,0.12)",
    2: "none",
    8: "0 5px 5px rgba(0, 0,0,0.15)",
  },
});
```

</details>

<details>
    <summary><code>utils.js</code></summary>

```js
export const testimonials = [
  {
    name: "Rahul Sharma",
    review:
      "Amazing shopping experience! The website is easy to navigate, and the checkout process was seamless. The product arrived on time and was exactly as described. Highly recommended!",
    rating: 5,
  },
  {
    name: "Priya Verma",
    review:
      "Great quality products at affordable prices. Customer service was very responsive and helped me track my order. Will definitely shop again!",
    rating: 5,
  },
  {
    name: "Ankit Singh",
    review:
      "I was impressed by the fast delivery and well-packaged items. The product quality exceeded my expectations. Looking forward to my next purchase!",
    rating: 5,
  },
  {
    name: "Simran Kaur",
    review:
      "The product was good, but the delivery took longer than expected. Customer support was helpful, but I wish the process was faster.",
    rating: 3,
  },
  {
    name: "Rajesh Mehta",
    review:
      "Decent experience overall. The website could use some improvements in filtering products. The checkout process was smooth, though.",
    rating: 3,
  },
  {
    name: "Pooja Agarwal",
    review:
      "The product was fine, but the packaging was slightly damaged. It didn’t affect the product inside, but better packaging would be appreciated.",
    rating: 3,
  },
  {
    name: "Arjun Malhotra",
    review:
      "Not a great experience. My order got delayed by 10 days, and customer support was slow to respond. The product was okay, but I expected better service.",
    rating: 2,
  },
  {
    name: "Neha Jain",
    review:
      "The product was not as described. I requested a return, but the process was complicated. Not very happy with the service.",
    rating: 1,
  },
  {
    name: "Vikram Kapoor",
    review:
      "Received the wrong product. Customer service was not helpful, and I had to wait a long time for a replacement. Disappointed!",
    rating: 1,
  },
];

export const monthNames = [
  "January",
  "February",
  "March",
  "April",
  "May",
  "June",
  "July",
  "August",
  "September",
  "October",
  "November",
  "December",
];
```

</details>


# Icons 

```js 

// Admin Sidebar icons.
import { AiOutlineDashboard } from "react-icons/ai";
import { BiCategory } from "react-icons/bi";
import { IoShirtOutline } from "react-icons/io5";
import { MdOutlineShoppingBag } from "react-icons/md";
import { LuUserRound } from "react-icons/lu";
import { IoMdStarOutline } from "react-icons/io";
import { MdOutlinePermMedia } from "react-icons/md";
import { RiCoupon2Line } from "react-icons/ri";

// Plus icon.
import { FiPlus } from "react-icons/fi";

// Admin dashboard icons.
import { BiCategory } from "react-icons/bi";
import { IoShirtOutline } from "react-icons/io5";
import { LuUserRound } from "react-icons/lu";
import { MdOutlineShoppingBag } from "react-icons/md";

// Star icon. 
import { MdOutlineStar } from "react-icons/md";

// Quick add component icons.  
import { BiCategory } from "react-icons/bi";
import { IoShirtOutline } from "react-icons/io5";
import { RiCoupon2Line } from "react-icons/ri";
import { MdOutlinePermMedia } from "react-icons/md";

// Home page icons. 
import { GoArrowRight } from "react-icons/go";
import { GiReturnArrow } from "react-icons/gi";
import { FaShippingFast } from "react-icons/fa";
import { BiSupport } from "react-icons/bi";
import { RiDiscountPercentFill } from "react-icons/ri";

// Circular close icon.
import { IoCloseCircleOutline } from "react-icons/io5";

// Checkout page shipping icon. 
import { FaShippingFast } from "react-icons/fa";

// my-account page icons. 
import { HiOutlineShoppingBag } from "react-icons/hi2";
import { IoCartOutline } from "react-icons/io5";

// Product details component icons.
import { IoIosStar } from "react-icons/io";
import { HiMinus } from "react-icons/hi";
import { HiPlus } from "react-icons/hi";

// Eye icons. 
import { FaRegEyeSlash } from "react-icons/fa";
import { FaRegEye } from "react-icons/fa6";

// Search icon.  
import { HiOutlineSearch } from "react-icons/hi";

// App sidebar close and arrow icon.
import { LuChevronRight } from "react-icons/lu";
import { IoMdClose } from "react-icons/io";

// Download icon. 
import { MdOutlineFileDownload } from "react-icons/md";

// Media component icons.  
import { BsThreeDotsVertical } from "react-icons/bs";
import { MdOutlineEdit } from "react-icons/md";
import { IoIosLink } from "react-icons/io";
import { AiOutlineDelete } from "react-icons/ai";

// Menu bar icon.  
import { RiMenu4Fill } from "react-icons/ri";

// User dropdown icon.  
import { IoShirtOutline } from "react-icons/io5";
import { MdOutlineShoppingBag } from "react-icons/md";

// Footer icons.  
import { IoLocationOutline } from "react-icons/io5";
import { IoMailOutline } from "react-icons/io5";
import { IoCallOutline } from "react-icons/io5";
import { AiOutlineYoutube } from "react-icons/ai";
import { FaInstagram } from "react-icons/fa";
import { RiFacebookCircleLine } from "react-icons/ri";
import { FiTwitter } from "react-icons/fi";
import { FaWhatsapp } from "react-icons/fa";

// Header icons.  
import { IoIosSearch } from "react-icons/io";
import { LuCircleUser } from "react-icons/lu";
import { IoMdMenu } from "react-icons/io";
import { IoMdClose } from "react-icons/io";

// Main slider icon. 
import { LuChevronLeft, LuChevronRight } from "react-icons/lu";

// Testimonial component icons.  
import { BsChatQuote } from "react-icons/bs";
import { IoMdStar } from "react-icons/io";

```