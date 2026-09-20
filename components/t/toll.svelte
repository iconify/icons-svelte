<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwuz_u2dz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nwuz_u2dz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:toll" {...props}></Icon>
