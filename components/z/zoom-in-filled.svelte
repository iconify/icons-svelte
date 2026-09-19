<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsivexdcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="nsivexdcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:zoom-in-filled" {...props}></Icon>
