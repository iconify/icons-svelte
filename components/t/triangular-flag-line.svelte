<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5ediybrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k5ediybrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:triangular-flag-line" {...props}></Icon>
