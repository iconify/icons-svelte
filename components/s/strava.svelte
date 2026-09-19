<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ireb7vb3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ireb7vb3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:strava" {...props}></Icon>
