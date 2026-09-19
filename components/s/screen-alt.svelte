<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwih3-_ho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="uwih3-_ho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:screen-alt" {...props}></Icon>
