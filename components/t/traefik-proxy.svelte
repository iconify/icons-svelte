<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc2uxhxzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uc2uxhxzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:traefik-proxy" {...props}></Icon>
