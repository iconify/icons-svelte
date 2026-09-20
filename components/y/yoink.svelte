<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec7pwm9zi.css';
import '../../css/w/wdns3gx2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ec7pwm9zi"/><path class="wdns3gx2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yoink" {...props}></Icon>
