<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfg2xib9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pfg2xib9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:secureai-tools-light" {...props}></Icon>
