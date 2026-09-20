<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt6gjyb0z.css';
import '../../css/h/hs9yxrbzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="tt6gjyb0z"/><path class="hs9yxrbzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:stairway" {...props}></Icon>
