<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3livcc1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3livcc1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sega" {...props}></Icon>
