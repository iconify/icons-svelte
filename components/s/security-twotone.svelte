<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxei3g.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-60.css';
import '../../css/f/fill-to-0_3.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxei3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:security-twotone" {...props}></Icon>
