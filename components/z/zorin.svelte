<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4shxhvly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t4shxhvly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:zorin" {...props}></Icon>
