<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td42iq_wv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="td42iq_wv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sipeed-light" {...props}></Icon>
