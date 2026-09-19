<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjlxl3bmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":440,"height":512};
const content = `<path class="fjlxl3bmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:staylinked" {...props}></Icon>
