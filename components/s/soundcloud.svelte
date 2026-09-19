<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mn3a8pm_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="mn3a8pm_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:soundcloud" {...props}></Icon>
