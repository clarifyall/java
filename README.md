	SimpleDateFormat sdf = new SimpleDateFormat("MM/dd/yyyy", Locale.US);
		sdf.setTimeZone(TimeZone.getTimeZone("America/New_York"));           
		System.out.println(sdf.format(new Date()));
