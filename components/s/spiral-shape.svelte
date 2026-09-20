<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oijq4ku3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oijq4ku3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:spiral-shape" {...props}></Icon>
