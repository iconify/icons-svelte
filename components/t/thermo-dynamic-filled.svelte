<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ch_ylrb6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ch_ylrb6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:thermo-dynamic-filled" {...props}></Icon>
