<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzv361beg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wzv361beg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:snapchat-solid" {...props}></Icon>
