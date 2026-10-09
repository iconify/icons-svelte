<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfw21bb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lfw21bb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:underfloor-heating-48" {...props}></Icon>
