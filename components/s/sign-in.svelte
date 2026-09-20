<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-fg1db2d.css';
import '../../css/f/frl31gg3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p-fg1db2d"/><path class="frl31gg3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:sign-in" {...props}></Icon>
