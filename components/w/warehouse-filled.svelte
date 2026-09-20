<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hia--8b1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hia--8b1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:warehouse-filled" {...props}></Icon>
