<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p76hqtbzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p76hqtbzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:the-red-yeti" {...props}></Icon>
