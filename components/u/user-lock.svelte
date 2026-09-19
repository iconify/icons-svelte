<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scu_z2bli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="scu_z2bli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:user-lock" {...props}></Icon>
