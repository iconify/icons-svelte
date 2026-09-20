<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6og-9b-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m6og-9b-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:squares-2x2-solid-expressive" {...props}></Icon>
