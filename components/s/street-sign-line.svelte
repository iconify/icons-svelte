<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_ge1pb_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_ge1pb_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:street-sign-line" {...props}></Icon>
