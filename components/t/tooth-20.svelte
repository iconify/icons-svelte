<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh2evfk1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yh2evfk1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tooth-20" {...props}></Icon>
