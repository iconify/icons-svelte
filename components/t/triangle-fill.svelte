<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vblmr_zyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vblmr_zyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:triangle-fill" {...props}></Icon>
