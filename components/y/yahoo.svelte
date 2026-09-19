<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twa7w--ja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="twa7w--ja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:yahoo" {...props}></Icon>
