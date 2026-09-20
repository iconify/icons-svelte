<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfhmwubgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kfhmwubgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:watch-2-remix" {...props}></Icon>
