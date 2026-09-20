<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r166oobxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="r166oobxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:tall-hat" {...props}></Icon>
