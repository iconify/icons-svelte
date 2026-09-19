<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8l390kbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="s8l390kbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:spell-check" {...props}></Icon>
