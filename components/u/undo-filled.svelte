<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kj7514b3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kj7514b3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:undo-filled" {...props}></Icon>
