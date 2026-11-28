<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb60x0cdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lb60x0cdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:tulip-heart" {...props}></Icon>
