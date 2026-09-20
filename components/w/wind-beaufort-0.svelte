<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp5ltcqbw.css';
import '../../css/w/wsnuap-ub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<defs><symbol id="SVG42U0UdPS" viewBox="0 0 342 234"><path class="bp5ltcqbw"/></symbol></defs><use width="342" height="234" href="#SVG42U0UdPS" transform="translate(85 139)"/><path class="wsnuap-ub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteocons:wind-beaufort-0" {...props}></Icon>
