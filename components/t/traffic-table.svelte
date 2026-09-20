<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kef3gpz4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kef3gpz4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:traffic-table" {...props}></Icon>
