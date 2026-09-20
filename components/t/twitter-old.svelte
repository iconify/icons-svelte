<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wix3a056v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wix3a056v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:twitter-old" {...props}></Icon>
