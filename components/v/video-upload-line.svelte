<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y30mjzbuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y30mjzbuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:video-upload-line" {...props}></Icon>
