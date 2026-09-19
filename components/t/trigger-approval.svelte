<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5r_51ldy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="m5r_51ldy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:trigger-approval" {...props}></Icon>
