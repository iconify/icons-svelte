<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg6ea-bsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gg6ea-bsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shot" {...props}></Icon>
