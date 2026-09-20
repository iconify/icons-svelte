<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flnsk_y9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="flnsk_y9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:runkeeper" {...props}></Icon>
