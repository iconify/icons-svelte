<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnzc5o18j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lnzc5o18j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tag-2-fill" {...props}></Icon>
