<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0v-_zcks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m0v-_zcks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rudder-dark" {...props}></Icon>
