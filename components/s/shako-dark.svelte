<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxufv2zqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qxufv2zqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:shako-dark" {...props}></Icon>
