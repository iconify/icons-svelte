<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x63-purll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x63-purll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:service-desk" {...props}></Icon>
