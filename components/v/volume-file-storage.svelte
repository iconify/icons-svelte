<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud8zcybxg.css';
import '../../css/s/snzv8lbca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ud8zcybxg"/><path class="snzv8lbca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:volume-file-storage" {...props}></Icon>
