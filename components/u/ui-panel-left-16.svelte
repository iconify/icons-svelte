<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrxhsjmcx.css';
import '../../css/v/v4t3l6h1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yrxhsjmcx"/><path clip-rule="evenodd" class="v4t3l6h1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:ui-panel-left-16" {...props}></Icon>
