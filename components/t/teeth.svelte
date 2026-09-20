<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zaixgqb7g.css';
import '../../css/r/r-2sp9a4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zaixgqb7g"/><path class="r-2sp9a4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:teeth" {...props}></Icon>
