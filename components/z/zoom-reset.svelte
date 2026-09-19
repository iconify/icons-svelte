<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hom3-lb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hom3-lb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:zoom-reset" {...props}></Icon>
