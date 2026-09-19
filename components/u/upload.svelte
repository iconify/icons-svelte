<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irr2v7bvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="irr2v7bvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:upload" {...props}></Icon>
