<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qig4g1byc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qig4g1byc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yopass-light" {...props}></Icon>
