<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7gkr3nsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="d7gkr3nsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:square-clock-solid" {...props}></Icon>
