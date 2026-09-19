<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp4_hpb0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fp4_hpb0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:user-check-filled" {...props}></Icon>
