<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck7oek4jj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ck7oek4jj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:sun-o" {...props}></Icon>
