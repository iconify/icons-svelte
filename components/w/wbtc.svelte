<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkfw2ofxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tkfw2ofxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:wbtc" {...props}></Icon>
