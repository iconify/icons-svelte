<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhwn_b2xm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="uhwn_b2xm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:safari" {...props}></Icon>
