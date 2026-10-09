<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw3xaacjo.css';
import '../../css/m/mscaq-vkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yw3xaacjo"/><path class="mscaq-vkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smoke-alarm-20" {...props}></Icon>
