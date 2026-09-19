<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmi7qy-ke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pmi7qy-ke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:window-terminal" {...props}></Icon>
