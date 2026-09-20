<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qoagr4blb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="qoagr4blb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:rss-alt" {...props}></Icon>
