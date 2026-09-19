<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbxxnv_xu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xbxxnv_xu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:slice-of-pizza" {...props}></Icon>
