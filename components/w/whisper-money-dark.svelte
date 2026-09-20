<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlj9kwion.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zlj9kwion"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:whisper-money-dark" {...props}></Icon>
