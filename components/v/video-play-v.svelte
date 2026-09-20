<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/armb_ptpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="armb_ptpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:video-play-v" {...props}></Icon>
