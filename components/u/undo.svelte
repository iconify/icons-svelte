<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojq3kenou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ojq3kenou st0"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:undo" {...props}></Icon>
