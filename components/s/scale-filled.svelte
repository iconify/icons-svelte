<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4yikcexh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="n4yikcexh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:scale-filled" {...props}></Icon>
