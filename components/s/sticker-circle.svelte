<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4gwydb5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b4gwydb5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:sticker-circle" {...props}></Icon>
