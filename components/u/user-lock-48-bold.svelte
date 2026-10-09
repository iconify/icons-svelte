<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stamzdbdq.css';
import '../../css/t/tusg1jm7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="stamzdbdq"/><path class="tusg1jm7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:user-lock-48-bold" {...props}></Icon>
