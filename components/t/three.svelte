<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5if0lb-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k5if0lb-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:three" {...props}></Icon>
