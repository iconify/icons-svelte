<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft7o93brm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ft7o93brm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:volume-filled" {...props}></Icon>
