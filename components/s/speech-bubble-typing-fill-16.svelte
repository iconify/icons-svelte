<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uu022rzoq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uu022rzoq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:speech-bubble-typing-fill-16" {...props}></Icon>
