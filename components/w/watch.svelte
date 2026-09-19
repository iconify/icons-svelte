<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x68ws0bxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x68ws0bxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:watch" {...props}></Icon>
