<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtt81nbxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="jtt81nbxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:wizards-of-the-coast" {...props}></Icon>
