<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6hsf421h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="k6hsf421h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:text-wrap-slash-light" {...props}></Icon>
