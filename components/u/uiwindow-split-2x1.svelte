<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo3ndbcqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="bo3ndbcqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:uiwindow-split-2x1" {...props}></Icon>
