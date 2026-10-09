<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia2yv5bfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ia2yv5bfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:users-48-bold" {...props}></Icon>
