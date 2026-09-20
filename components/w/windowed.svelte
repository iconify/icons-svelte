<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4ynxzpzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="c4ynxzpzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:windowed" {...props}></Icon>
