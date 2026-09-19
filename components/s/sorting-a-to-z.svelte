<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgbfwbbcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jgbfwbbcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:sorting-a-to-z" {...props}></Icon>
