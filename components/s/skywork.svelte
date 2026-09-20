<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5zqrfbjz.css';
import '../../css/c/cjj93mxay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n5zqrfbjz"/><path class="cjj93mxay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:skywork" {...props}></Icon>
