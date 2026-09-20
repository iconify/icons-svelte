<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/db7rvqw0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":405};
const content = `<path class="db7rvqw0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:statelydotai-light" {...props}></Icon>
