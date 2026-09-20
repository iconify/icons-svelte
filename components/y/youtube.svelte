<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g21r9t2-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="g21r9t2-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:youtube" {...props}></Icon>
