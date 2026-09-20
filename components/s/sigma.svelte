<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lveycmbwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="lveycmbwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:sigma" {...props}></Icon>
