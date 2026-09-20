<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvbnvty7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nvbnvty7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:volume-off-fill" {...props}></Icon>
