<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvwtb5uoe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvwtb5uoe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:vr-headset-gloss" {...props}></Icon>
