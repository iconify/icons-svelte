<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmdz1kbua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cmdz1kbua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:steering-wheel" {...props}></Icon>
