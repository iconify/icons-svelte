<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zujffeb8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zujffeb8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:smart-home4-filled" {...props}></Icon>
