<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0xwpgbvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="x0xwpgbvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:swagger" {...props}></Icon>
