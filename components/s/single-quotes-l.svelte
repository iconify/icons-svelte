<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j86jxwbzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j86jxwbzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:single-quotes-l" {...props}></Icon>
