<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg5v6ebyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mg5v6ebyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:server-process" {...props}></Icon>
