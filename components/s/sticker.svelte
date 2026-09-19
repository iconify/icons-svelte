<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_tqzxbbs.css';
import '../../css/d/dp4lw14sb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_tqzxbbs"/><path class="dp4lw14sb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:sticker" {...props}></Icon>
