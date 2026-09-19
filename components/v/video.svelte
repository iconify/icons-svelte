<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etwhu2bjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="etwhu2bjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:video" {...props}></Icon>
