<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lznnucceq.css';
import '../../css/m/muuvzwbbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lznnucceq"/><path class="muuvzwbbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:search-split-duotone" {...props}></Icon>
