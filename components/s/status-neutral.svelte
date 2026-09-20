<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9s-xjbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="i9s-xjbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:status-neutral" {...props}></Icon>
