<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap_-e3b3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ap_-e3b3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:tools" {...props}></Icon>
