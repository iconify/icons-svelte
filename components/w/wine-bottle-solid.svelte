<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_89rtb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x_89rtb6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:wine-bottle-solid" {...props}></Icon>
