<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf11m8dlt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bf11m8dlt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:srn" {...props}></Icon>
