<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3x0_hb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3x0_hb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:swap-diagonal-filled" {...props}></Icon>
