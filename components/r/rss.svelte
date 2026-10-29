<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew13tbxvb.css';
import '../../css/a/al19bfb5b.css';
import '../../css/j/jmiuoqhtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ew13tbxvb wm-k"/><path class="al19bfb5b wm-a"/><path class="jmiuoqhtu wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:rss" {...props}></Icon>
