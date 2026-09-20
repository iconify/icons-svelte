<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcje6dbpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wcje6dbpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:stamp" {...props}></Icon>
