<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fueex0wmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fueex0wmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:stremio" {...props}></Icon>
