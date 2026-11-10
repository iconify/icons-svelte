<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf1tzwukj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gf1tzwukj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:user-exclamation-point-filled" {...props}></Icon>
