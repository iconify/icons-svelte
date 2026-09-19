<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j79x-vugx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="j79x-vugx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:thumbs-down" {...props}></Icon>
