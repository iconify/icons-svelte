<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo-nkybxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jo-nkybxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:square-medium" {...props}></Icon>
