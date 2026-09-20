<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg-dvgjit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fg-dvgjit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:star-fall3" {...props}></Icon>
