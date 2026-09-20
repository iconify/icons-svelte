<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n77hk2kzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="n77hk2kzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:three-dots-horizontal" {...props}></Icon>
