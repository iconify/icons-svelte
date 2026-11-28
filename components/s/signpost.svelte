<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z72rlsblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z72rlsblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:signpost" {...props}></Icon>
