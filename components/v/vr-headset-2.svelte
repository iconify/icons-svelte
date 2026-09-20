<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuym8zbni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="vuym8zbni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:vr-headset-2" {...props}></Icon>
