<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhgxw2lrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhgxw2lrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:slack-fill" {...props}></Icon>
