<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpz66wbfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wpz66wbfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:rss-error" {...props}></Icon>
