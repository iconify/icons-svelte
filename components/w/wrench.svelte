<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlv3j1b6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="vlv3j1b6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:wrench" {...props}></Icon>
