<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lv9h8fb8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lv9h8fb8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:suitcase-rolling-remix" {...props}></Icon>
