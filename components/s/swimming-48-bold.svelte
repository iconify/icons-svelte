<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozrn3bc7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ozrn3bc7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:swimming-48-bold" {...props}></Icon>
