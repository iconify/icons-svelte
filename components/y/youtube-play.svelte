<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvk456bgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":34,"height":24};
const content = `<path class="zvk456bgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:youtube-play" {...props}></Icon>
