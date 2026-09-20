<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyis771pa.css';
import '../../css/k/kfc9attts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pyis771pa"/><path class="kfc9attts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:slide2" {...props}></Icon>
