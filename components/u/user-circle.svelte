<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-001pbgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="q-001pbgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:user-circle" {...props}></Icon>
