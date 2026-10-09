<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y79i0r8qi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y79i0r8qi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smr-48-bold" {...props}></Icon>
