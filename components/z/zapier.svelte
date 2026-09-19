<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipu15wbwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ipu15wbwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:zapier" {...props}></Icon>
