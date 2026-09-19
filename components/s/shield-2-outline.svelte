<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qigmqebvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="qigmqebvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:shield-2-outline" {...props}></Icon>
