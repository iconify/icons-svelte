<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mb4-j_brm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mb4-j_brm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:sun-line" {...props}></Icon>
