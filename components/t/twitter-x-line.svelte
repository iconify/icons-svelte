<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmb6m4bku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zmb6m4bku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:twitter-x-line" {...props}></Icon>
