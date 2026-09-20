<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnl6okbyg.css';
import '../../css/d/db9d_bb7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hnl6okbyg"/><path class="db9d_bb7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:storage" {...props}></Icon>
