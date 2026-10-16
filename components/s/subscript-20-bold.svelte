<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy3-jm4dn.css';
import '../../css/h/h0d_lm9zw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="iy3-jm4dn"/><path class="h0d_lm9zw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:subscript-20-bold" {...props}></Icon>
