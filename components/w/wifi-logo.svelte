<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mds117d_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":34,"height":24};
const content = `<path class="mds117d_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:wifi-logo" {...props}></Icon>
