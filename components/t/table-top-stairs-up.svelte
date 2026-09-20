<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1n_l6qgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="c1n_l6qgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:table-top-stairs-up" {...props}></Icon>
