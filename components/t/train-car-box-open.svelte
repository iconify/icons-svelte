<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmpfof1_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jmpfof1_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:train-car-box-open" {...props}></Icon>
