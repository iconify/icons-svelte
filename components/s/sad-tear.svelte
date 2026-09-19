<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd-v9xn1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="fd-v9xn1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:sad-tear" {...props}></Icon>
