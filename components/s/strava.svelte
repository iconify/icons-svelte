<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg6mzf6sl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lg6mzf6sl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:strava" {...props}></Icon>
