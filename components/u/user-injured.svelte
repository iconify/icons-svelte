<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwbmi7zqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nwbmi7zqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:user-injured" {...props}></Icon>
