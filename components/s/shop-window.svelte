<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdzwg8bxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wdzwg8bxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:shop-window" {...props}></Icon>
