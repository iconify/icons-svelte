<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du81u6b2b.css';
import '../../css/u/ut-e98spq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="du81u6b2b"/><path class="ut-e98spq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:synchronize-arrows" {...props}></Icon>
