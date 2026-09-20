<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/db_f8kbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="db_f8kbhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:session-ai" {...props}></Icon>
