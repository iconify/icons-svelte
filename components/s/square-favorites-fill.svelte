<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq16369sx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="fq16369sx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:square-favorites-fill" {...props}></Icon>
