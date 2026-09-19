<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lla7bcj_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lla7bcj_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:vet" {...props}></Icon>
