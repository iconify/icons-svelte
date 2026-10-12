<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe2bw_bvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oe2bw_bvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:user-star-filled" {...props}></Icon>
