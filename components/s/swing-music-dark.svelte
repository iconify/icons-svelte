<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f08a3zbug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f08a3zbug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:swing-music-dark" {...props}></Icon>
