<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0n3v1bye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z0n3v1bye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:suitcase-under-list-beside-checkmark" {...props}></Icon>
