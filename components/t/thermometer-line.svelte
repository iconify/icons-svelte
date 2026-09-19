<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7e_w-tnk.css';
import '../../css/i/i8klc0q7m.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 n7e_w-tnk"/><path class="clr-i-outline clr-i-outline-path-2 i8klc0q7m"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:thermometer-line" {...props}></Icon>
