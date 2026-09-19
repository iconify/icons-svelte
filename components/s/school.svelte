<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjp2ig6jr.css';
import '../../css/m/mch78aboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qjp2ig6jr"/><path class="mch78aboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:school" {...props}></Icon>
