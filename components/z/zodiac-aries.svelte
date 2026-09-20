<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0z_zggyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0z_zggyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:zodiac-aries" {...props}></Icon>
