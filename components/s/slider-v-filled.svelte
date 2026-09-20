<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3-hvq8uv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o3-hvq8uv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:slider-v-filled" {...props}></Icon>
