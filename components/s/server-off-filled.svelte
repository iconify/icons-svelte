<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx0z78bot.css';
import '../../css/t/tdaucbcdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tx0z78bot"/><path class="tdaucbcdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:server-off-filled" {...props}></Icon>
