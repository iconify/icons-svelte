<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2pz2ibnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary v2pz2ibnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:zodiac-aries-duotone" {...props}></Icon>
