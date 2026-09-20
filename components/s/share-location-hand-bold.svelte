<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vho_s5bgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vho_s5bgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:share-location-hand-bold" {...props}></Icon>
