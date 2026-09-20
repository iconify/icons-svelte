<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb_el90_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qb_el90_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:tooth" {...props}></Icon>
