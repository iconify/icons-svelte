<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klpdtzbai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="klpdtzbai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:speech-bubble-typing-fill-12" {...props}></Icon>
