<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gi_-iqbum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gi_-iqbum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:skip-back" {...props}></Icon>
