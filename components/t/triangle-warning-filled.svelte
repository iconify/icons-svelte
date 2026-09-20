<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhn31wqfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qhn31wqfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:triangle-warning-filled" {...props}></Icon>
