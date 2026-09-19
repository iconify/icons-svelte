<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzerl6y7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="xzerl6y7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:sort-down-circle-fill" {...props}></Icon>
