<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uivcxx24w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uivcxx24w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:surface-front-filled" {...props}></Icon>
