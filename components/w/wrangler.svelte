<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmab-___r.css';
import '../../css/e/emuyr7bck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dmab-___r"/><path class="emuyr7bck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:wrangler" {...props}></Icon>
