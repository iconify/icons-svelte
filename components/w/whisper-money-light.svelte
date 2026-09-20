<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vv5k-0bpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vv5k-0bpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:whisper-money-light" {...props}></Icon>
