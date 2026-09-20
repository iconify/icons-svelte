<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swc4nv0cw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="swc4nv0cw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:transport" {...props}></Icon>
