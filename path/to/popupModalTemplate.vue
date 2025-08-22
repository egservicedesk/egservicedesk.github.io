<template>
  <div class="modal">
    <h2>Contact Follow-up</h2>
    <form>
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>

      <label for="contact-method">Contact Method:</label>
      <input type="text" id="contact-method" name="contact-method" placeholder="Phone/Email/Kaseya" required>

      <label for="contact-number">Contact Number:</label>
      <input type="text" id="contact-number" name="contact-number" required>

      <label for="callback-attempt">Callback Attempt:</label>
      <textarea id="callback-attempt" name="callback-attempt" placeholder="1st attempt - callback, left a voicemail, message in Kaseya, and Email; 2nd attempt - callback, left a voicemail, message in Kaseya, and Email; 3rd attempt - callback, left a voicemail, message in Kaseya, Email store and DM; No response from store and DM after 3rd attempt. Closing ticket" required></textarea>

      <label for="action-owner">Action Owner:</label>
      <input type="text" id="action-owner" name="action-owner" placeholder="Marketspark, Evolve, Servicedesk, Helpdesk, L2, FTS, FSS, Escalation Team, Marketing Team, etc." required>

      <label for="next-action">Next Action Required:</label>
      <input type="text" id="next-action" name="next-action" required>

      <button type="submit">Follow-up/Call Attempt</button>
    </form>
  </div>
</template>