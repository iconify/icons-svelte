<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5e-1qbcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5e-1qbcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:stair-stepper-fill" {...props}></Icon>
