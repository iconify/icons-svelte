<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/docw4db7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="docw4db7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:table-list" {...props}></Icon>
