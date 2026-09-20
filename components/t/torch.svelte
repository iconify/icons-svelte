<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x86x4fbpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="x86x4fbpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:torch" {...props}></Icon>
