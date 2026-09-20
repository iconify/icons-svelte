<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd_h-2b1r.css';
import '../../css/b/bbae6rbgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cd_h-2b1r"/><path class="bbae6rbgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rss-2-line" {...props}></Icon>
