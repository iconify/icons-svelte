<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5tdg8tgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b5tdg8tgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zigbee2mqtt-light" {...props}></Icon>
