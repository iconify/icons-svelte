<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvc_zmb-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rvc_zmb-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:shape-2-fill" {...props}></Icon>
