<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxut9fbjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="uxut9fbjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:wifi-disabled" {...props}></Icon>
