<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4s6twb3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a4s6twb3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:video-outline" {...props}></Icon>
