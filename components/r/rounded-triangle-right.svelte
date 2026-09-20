<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9t_h3jeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="n9t_h3jeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:rounded-triangle-right" {...props}></Icon>
