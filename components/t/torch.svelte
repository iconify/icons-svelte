<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khw-9n4qe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="khw-9n4qe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:torch" {...props}></Icon>
