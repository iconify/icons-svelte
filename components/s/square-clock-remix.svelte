<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja23jp77d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ja23jp77d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:square-clock-remix" {...props}></Icon>
