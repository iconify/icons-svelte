<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldz9pm7fd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ldz9pm7fd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:trail-sign" {...props}></Icon>
