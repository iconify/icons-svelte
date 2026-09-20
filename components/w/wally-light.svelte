<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myfiu2y2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="myfiu2y2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wally-light" {...props}></Icon>
