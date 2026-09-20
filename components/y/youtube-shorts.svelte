<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4i3bob8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4i3bob8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:youtube-shorts" {...props}></Icon>
