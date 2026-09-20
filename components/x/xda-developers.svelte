<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt_88-bgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kt_88-bgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:xda-developers" {...props}></Icon>
