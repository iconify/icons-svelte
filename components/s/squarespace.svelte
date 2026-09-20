<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8v_38bzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z8v_38bzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:squarespace" {...props}></Icon>
