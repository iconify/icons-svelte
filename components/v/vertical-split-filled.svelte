<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0w1_nr1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d0w1_nr1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:vertical-split-filled" {...props}></Icon>
