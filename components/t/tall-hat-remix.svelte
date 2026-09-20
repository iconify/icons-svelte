<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-l70pe5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c-l70pe5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:tall-hat-remix" {...props}></Icon>
