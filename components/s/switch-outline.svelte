<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk6-1wqqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lk6-1wqqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:switch-outline" {...props}></Icon>
