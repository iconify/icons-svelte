<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usmti8bmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="usmti8bmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:scanner-bar-code-remix" {...props}></Icon>
