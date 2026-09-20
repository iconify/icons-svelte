<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duf3r5bbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="duf3r5bbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:share-megaphone" {...props}></Icon>
