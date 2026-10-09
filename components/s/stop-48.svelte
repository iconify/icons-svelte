<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd358i0ji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hd358i0ji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:stop-48" {...props}></Icon>
