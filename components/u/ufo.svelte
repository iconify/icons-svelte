<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8py-sbum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y8py-sbum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:ufo" {...props}></Icon>
