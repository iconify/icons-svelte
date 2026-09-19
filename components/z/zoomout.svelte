<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk15v_fiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":766};
const content = `<path class="uk15v_fiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:zoomout" {...props}></Icon>
