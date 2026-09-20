<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv51d6bao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fv51d6bao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:sensor-fill" {...props}></Icon>
