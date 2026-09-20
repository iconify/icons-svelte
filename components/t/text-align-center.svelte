<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-3x4kwuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-3x4kwuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:text-align-center" {...props}></Icon>
