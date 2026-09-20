<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdmw0mdax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jdmw0mdax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wavelog-light" {...props}></Icon>
