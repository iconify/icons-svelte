<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzf8385tp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qzf8385tp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tally-mark-5" {...props}></Icon>
