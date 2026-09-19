<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk18bmbgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yk18bmbgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:untappd" {...props}></Icon>
