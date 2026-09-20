<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vaebqy2hx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":192,"height":175};
const content = `<path class="vaebqy2hx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vlt-light" {...props}></Icon>
