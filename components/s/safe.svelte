<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d186mbb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="d186mbb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:safe" {...props}></Icon>
