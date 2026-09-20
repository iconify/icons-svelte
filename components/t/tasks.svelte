<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7thvyevl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q7thvyevl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:tasks" {...props}></Icon>
