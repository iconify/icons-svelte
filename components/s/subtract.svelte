<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti0yokb0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ti0yokb0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:subtract" {...props}></Icon>
