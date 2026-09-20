<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsq8sfrxg.css';
import '../../css/f/fkt9bwryo.css';
import '../../css/b/b8ni7-bky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dsq8sfrxg"/><path class="fkt9bwryo"/><path class="b8ni7-bky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tiktok" {...props}></Icon>
