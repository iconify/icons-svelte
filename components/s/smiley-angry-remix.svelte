<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upo-q5bnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="upo-q5bnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:smiley-angry-remix" {...props}></Icon>
