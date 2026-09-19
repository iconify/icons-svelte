<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf_7ibbbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="mf_7ibbbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:square-xmark" {...props}></Icon>
