<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh2_u5bkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lh2_u5bkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:user-minus-48-bold" {...props}></Icon>
