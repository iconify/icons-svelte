<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bspz8r2wy.css';
import '../../css/s/s-uxakxfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bspz8r2wy"/><path class="s-uxakxfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:verified-24" {...props}></Icon>
