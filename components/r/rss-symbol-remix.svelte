<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekj4x2bnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ekj4x2bnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:rss-symbol-remix" {...props}></Icon>
