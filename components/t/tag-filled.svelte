<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-pgsfpfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="h-pgsfpfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:tag-filled" {...props}></Icon>
