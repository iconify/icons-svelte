<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2j8np86l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p2j8np86l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:token-swap-line" {...props}></Icon>
