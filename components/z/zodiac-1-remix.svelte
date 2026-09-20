<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klbr89erq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="klbr89erq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:zodiac-1-remix" {...props}></Icon>
