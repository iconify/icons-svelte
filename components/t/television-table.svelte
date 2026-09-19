<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4hnid7qo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j4hnid7qo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:television-table" {...props}></Icon>
