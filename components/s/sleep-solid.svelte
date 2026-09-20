<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6xxs4b3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="u6xxs4b3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:sleep-solid" {...props}></Icon>
