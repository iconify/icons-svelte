<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brtpu-bnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":22.5,"top":13.5};
const content = `<path class="brtpu-bnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vvveb-cms" {...props}></Icon>
