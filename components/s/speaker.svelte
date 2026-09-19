<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpe64o2wm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="wpe64o2wm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:speaker" {...props}></Icon>
