<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7towac9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x7towac9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:video-line" {...props}></Icon>
