<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgw1eqx5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="rgw1eqx5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:videocam-switch" {...props}></Icon>
