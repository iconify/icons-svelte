<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opnjybc5u.css';
import '../../css/a/afp1jxb0a.css';
import '../../css/k/klb71kbpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="opnjybc5u"/><path class="afp1jxb0a"/><path clip-rule="evenodd" class="klb71kbpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:video-file-camera" {...props}></Icon>
