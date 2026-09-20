<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-o-n3boq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="m-o-n3boq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:terminal" {...props}></Icon>
