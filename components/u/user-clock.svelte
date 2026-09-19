<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iu_mcwbds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="iu_mcwbds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:user-clock" {...props}></Icon>
