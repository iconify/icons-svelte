<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhm9gv9uy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="lhm9gv9uy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:tag-text" {...props}></Icon>
