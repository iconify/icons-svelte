<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w80hshjhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w80hshjhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:thumbs-up-double-filled" {...props}></Icon>
