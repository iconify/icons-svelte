<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qc99t7udr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qc99t7udr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:share-16-solid" {...props}></Icon>
