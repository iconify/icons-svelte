<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyfsfosee.css';
import '../../css/g/giof89hnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wyfsfosee"/><path clip-rule="evenodd" class="giof89hnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:social-whatsapp" {...props}></Icon>
