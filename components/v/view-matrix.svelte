<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcor-1yvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xcor-1yvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:view-matrix" {...props}></Icon>
