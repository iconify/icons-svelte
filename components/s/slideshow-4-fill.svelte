<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8-sadbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p8-sadbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:slideshow-4-fill" {...props}></Icon>
