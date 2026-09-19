<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljone413y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ljone413y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:triangle-up" {...props}></Icon>
