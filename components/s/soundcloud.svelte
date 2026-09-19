<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vst2324hk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vst2324hk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:soundcloud" {...props}></Icon>
