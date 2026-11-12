<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de1_e96at.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="de1_e96at"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tvheadend-dark" {...props}></Icon>
