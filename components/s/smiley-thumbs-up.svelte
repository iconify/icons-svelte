<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx2nxk0bk.css';
import '../../css/n/ndzomeb7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kx2nxk0bk"/><path class="ndzomeb7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:smiley-thumbs-up" {...props}></Icon>
