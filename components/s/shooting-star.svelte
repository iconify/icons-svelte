<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq8uafule.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uq8uafule"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:shooting-star" {...props}></Icon>
