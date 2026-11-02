<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm1hffcgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nm1hffcgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:send-line" {...props}></Icon>
