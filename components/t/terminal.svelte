<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmx3q3erz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mmx3q3erz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:terminal" {...props}></Icon>
