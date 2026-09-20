<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzkp8bbpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mzkp8bbpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:yamaha-motor-corporation" {...props}></Icon>
