<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4xw6ab6k.css';
import '../../css/x/xvdg5pbnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j4xw6ab6k"/><path class="xvdg5pbnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:train-48" {...props}></Icon>
