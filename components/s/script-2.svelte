<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl3z94bis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yl3z94bis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:script-2" {...props}></Icon>
