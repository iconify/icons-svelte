<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbi1n57ce.css';
import '../../css/g/gwi370brj.css';
import '../../css/l/lblj8jhet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bbi1n57ce"/><path class="gwi370brj"/><path class="lblj8jhet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:volume-mute" {...props}></Icon>
