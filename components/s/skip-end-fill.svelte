<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1b2lsb1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o1b2lsb1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:skip-end-fill" {...props}></Icon>
