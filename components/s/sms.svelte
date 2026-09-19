<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_d8j4ckm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a_d8j4ckm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:sms" {...props}></Icon>
