<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb7u_8b3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":960};
const content = `<path class="bb7u_8b3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:tuneinalt" {...props}></Icon>
