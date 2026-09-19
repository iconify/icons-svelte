<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwqxrzb-l.css';
import '../../css/s/s18h12q8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qwqxrzb-l"/><path class="s18h12q8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:traffic-event" {...props}></Icon>
