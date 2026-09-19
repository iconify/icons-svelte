<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jat4aubqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jat4aubqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:sort-numeric-up" {...props}></Icon>
