<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kinzzobxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":718,"height":669};
const content = `<path class="kinzzobxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:user" {...props}></Icon>
