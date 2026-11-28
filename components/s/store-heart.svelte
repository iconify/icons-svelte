<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq35xtbeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mq35xtbeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:store-heart" {...props}></Icon>
