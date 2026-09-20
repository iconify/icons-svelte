<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj_mtab2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="fj_mtab2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:table-top-vertical-stairs-ascend-down" {...props}></Icon>
