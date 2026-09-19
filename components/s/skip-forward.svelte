<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvzc1fbtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bvzc1fbtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:skip-forward" {...props}></Icon>
