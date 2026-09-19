<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5fiz9wbv.css';
import '../../css/i/i2gtjkbwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w5fiz9wbv"/><path class="i2gtjkbwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:shield-half" {...props}></Icon>
