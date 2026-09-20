<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_3cypb2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="w_3cypb2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:town-hall-11" {...props}></Icon>
