<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj0gsaczy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bj0gsaczy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:speed-table" {...props}></Icon>
