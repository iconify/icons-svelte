<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv8ko8b5d.css';
import '../../css/s/sttlk4byq.css';
import '../../css/m/mgxiggbbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gv8ko8b5d"/><path class="sttlk4byq"/><path class="mgxiggbbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:volume-mute-sharp" {...props}></Icon>
