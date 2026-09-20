<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nobvpzbdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nobvpzbdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:stop-music-16" {...props}></Icon>
