<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq-j5olxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="vq-j5olxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:uniregistry" {...props}></Icon>
