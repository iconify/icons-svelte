<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5a6n0a1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="b5a6n0a1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:swift" {...props}></Icon>
