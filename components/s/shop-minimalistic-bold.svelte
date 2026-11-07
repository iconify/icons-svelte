<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg0ekvbvc.css';
import '../../css/m/mkq5lkj0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gg0ekvbvc"/><path class="mkq5lkj0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shop-minimalistic-bold" {...props}></Icon>
