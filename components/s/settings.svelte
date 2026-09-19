<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5mm9zbyw.css';
import '../../css/p/phow5bc9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b5mm9zbyw"/><path class="phow5bc9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:settings" {...props}></Icon>
