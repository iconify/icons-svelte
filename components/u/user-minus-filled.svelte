<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0vebbm1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t0vebbm1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:user-minus-filled" {...props}></Icon>
