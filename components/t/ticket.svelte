<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezz8hjg-s.css';
import '../../css/u/uj_v03r8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ezz8hjg-s"/><path class="uj_v03r8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:ticket" {...props}></Icon>
