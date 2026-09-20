<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv1mpk7pw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hv1mpk7pw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:target-account" {...props}></Icon>
