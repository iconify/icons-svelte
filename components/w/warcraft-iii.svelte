<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrwpp37dl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wrwpp37dl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:warcraft-iii" {...props}></Icon>
