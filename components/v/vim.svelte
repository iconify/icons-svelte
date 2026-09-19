<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kozflou_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kozflou_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:vim" {...props}></Icon>
