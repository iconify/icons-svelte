<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cambr2b9u.css';
import '../../css/i/iotq56wry.css';
import '../../css/j/jhhngsf8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cambr2b9u"/><path class="iotq56wry"/><path class="jhhngsf8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:text-cursor-20" {...props}></Icon>
