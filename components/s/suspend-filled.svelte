<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wndymkbrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wndymkbrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:suspend-filled" {...props}></Icon>
