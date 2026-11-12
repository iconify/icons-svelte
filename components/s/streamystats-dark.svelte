<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyop2kbkj.css';
import '../../css/s/sna9uxb8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kyop2kbkj"/><path class="sna9uxb8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:streamystats-dark" {...props}></Icon>
