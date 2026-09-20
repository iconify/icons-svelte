<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdy7tmvfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="cdy7tmvfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:trolley" {...props}></Icon>
