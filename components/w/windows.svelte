<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrts1unsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":88,"height":88};
const content = `<path class="yrts1unsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:windows" {...props}></Icon>
