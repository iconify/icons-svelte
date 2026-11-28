<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mid5d7o1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mid5d7o1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:video-call-check" {...props}></Icon>
