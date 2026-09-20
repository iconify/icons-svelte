<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlj-17bjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="dlj-17bjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:top-align-filled" {...props}></Icon>
