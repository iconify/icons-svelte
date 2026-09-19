<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw6pplx8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yw6pplx8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:unsplash" {...props}></Icon>
