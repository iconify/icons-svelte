<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqr0_gxzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uqr0_gxzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:sidebar-fill-20" {...props}></Icon>
