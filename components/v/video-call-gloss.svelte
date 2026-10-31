<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yerfd1kgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yerfd1kgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:video-call-gloss" {...props}></Icon>
