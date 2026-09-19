<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ju-rj399k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ju-rj399k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:translate-hebrew-latin" {...props}></Icon>
