<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjqeexs3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yjqeexs3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:video-call-bold" {...props}></Icon>
