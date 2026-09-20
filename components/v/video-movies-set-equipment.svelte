<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqxvh-bno.css';
import '../../css/j/jheje3btr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wqxvh-bno"/><path class="jheje3btr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:video-movies-set-equipment" {...props}></Icon>
