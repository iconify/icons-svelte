<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox2enz3rd.css';
import '../../css/g/gycyi0r7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ox2enz3rd"/><path class="gycyi0r7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:sliders-24" {...props}></Icon>
