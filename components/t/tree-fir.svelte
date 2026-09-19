<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yx1nhvb9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yx1nhvb9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:tree-fir" {...props}></Icon>
