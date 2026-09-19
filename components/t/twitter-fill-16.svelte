<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tu6haob4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tu6haob4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:twitter-fill-16" {...props}></Icon>
