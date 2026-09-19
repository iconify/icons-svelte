<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snsic7b1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="snsic7b1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:slider-alt" {...props}></Icon>
