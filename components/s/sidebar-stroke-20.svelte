<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8i2i55cm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h8i2i55cm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:sidebar-stroke-20" {...props}></Icon>
