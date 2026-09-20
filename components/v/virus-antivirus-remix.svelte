<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wc8vzvbgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wc8vzvbgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:virus-antivirus-remix" {...props}></Icon>
