<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agtuo0byi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="agtuo0byi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:tree-04" {...props}></Icon>
