<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b441swb4b.css';
import '../../css/f/fkf53bc3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b441swb4b"/><path class="fkf53bc3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:single-select-16" {...props}></Icon>
