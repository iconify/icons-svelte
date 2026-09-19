<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-u3pzdzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="f-u3pzdzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:upside-down-face" {...props}></Icon>
