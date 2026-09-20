<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yig-g3btl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="yig-g3btl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:wave" {...props}></Icon>
