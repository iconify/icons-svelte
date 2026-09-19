<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkx2bjwdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="kkx2bjwdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:speech-bubble-conversation-stroke-12" {...props}></Icon>
