<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds65t-b6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ds65t-b6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:video-player" {...props}></Icon>
