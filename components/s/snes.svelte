<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzv8w_bxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzv8w_bxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:snes" {...props}></Icon>
