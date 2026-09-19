<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1s3-9vbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a1s3-9vbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:twitter-filled" {...props}></Icon>
