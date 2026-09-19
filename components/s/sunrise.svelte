<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us3jq0bxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="us3jq0bxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:sunrise" {...props}></Icon>
