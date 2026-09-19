<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxxo1bbhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":770,"height":1024};
const content = `<path class="oxxo1bbhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:tagvertical" {...props}></Icon>
