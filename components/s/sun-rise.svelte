<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_59ekgyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z_59ekgyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:sun-rise" {...props}></Icon>
