<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwxtb_fhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hwxtb_fhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:sprout-filled" {...props}></Icon>
