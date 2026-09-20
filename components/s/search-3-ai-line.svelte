<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owihpxbhp.css';
import '../../css/b/b3rcvrrsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="owihpxbhp"/><path class="b3rcvrrsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:search-3-ai-line" {...props}></Icon>
