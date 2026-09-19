<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq2-meouw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fq2-meouw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:sai" {...props}></Icon>
