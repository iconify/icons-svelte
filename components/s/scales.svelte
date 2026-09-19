<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbg954-7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xbg954-7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:scales" {...props}></Icon>
