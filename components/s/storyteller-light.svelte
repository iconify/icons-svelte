<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frshv9b_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="frshv9b_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:storyteller-light" {...props}></Icon>
