<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh0fupbic.css';
import '../../css/u/u9p7tmx1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lh0fupbic"/><path class="u9p7tmx1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:t-shirt-bold-duotone" {...props}></Icon>
