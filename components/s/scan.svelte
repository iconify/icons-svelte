<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_qdgacsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_qdgacsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:scan" {...props}></Icon>
