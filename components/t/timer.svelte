<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm_8qdbtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="dm_8qdbtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:timer" {...props}></Icon>
