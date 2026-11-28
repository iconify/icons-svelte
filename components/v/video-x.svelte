<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpqw4db6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qpqw4db6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:video-x" {...props}></Icon>
