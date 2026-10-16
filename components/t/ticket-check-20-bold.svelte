<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sssfo6btx.css';
import '../../css/t/tld7w6b8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sssfo6btx"/><path class="tld7w6b8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ticket-check-20-bold" {...props}></Icon>
