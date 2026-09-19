<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/robw075fr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="robw075fr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:user-circle" {...props}></Icon>
