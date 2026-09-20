<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1b_g1bii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s1b_g1bii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:text-square-remix" {...props}></Icon>
