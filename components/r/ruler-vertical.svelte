<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgztnybqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tgztnybqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:ruler-vertical" {...props}></Icon>
