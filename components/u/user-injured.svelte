<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3jklobzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="q3jklobzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:user-injured" {...props}></Icon>
