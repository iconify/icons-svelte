<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwe8ukbwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1920};
const content = `<path class="uwe8ukbwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:wedding-cake" {...props}></Icon>
