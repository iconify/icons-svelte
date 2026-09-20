<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a96pf-b5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a96pf-b5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:unlock" {...props}></Icon>
