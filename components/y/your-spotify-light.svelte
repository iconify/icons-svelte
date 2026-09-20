<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5sww7zir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l5sww7zir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:your-spotify-light" {...props}></Icon>
