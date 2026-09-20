<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok_5v3ylq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ok_5v3ylq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:washing-machine" {...props}></Icon>
