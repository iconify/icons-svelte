<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_9rovs-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="f_9rovs-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:skype" {...props}></Icon>
