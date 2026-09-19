<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0mf2hb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k0mf2hb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:wine-bottle-outline" {...props}></Icon>
