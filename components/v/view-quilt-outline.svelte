<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmz1f45_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pmz1f45_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:view-quilt-outline" {...props}></Icon>
