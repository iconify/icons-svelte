<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8ann5b2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u8ann5b2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sat1" {...props}></Icon>
