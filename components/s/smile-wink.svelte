<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khfbewbnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="khfbewbnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:smile-wink" {...props}></Icon>
