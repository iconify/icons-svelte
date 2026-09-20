<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2xt3z6tq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="r2xt3z6tq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:sigma" {...props}></Icon>
