<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1sj30ber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="j1sj30ber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:wifi-antenna" {...props}></Icon>
