<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyr___g3f.css';
import '../../css/d/dfv392bxj.css';
import '../../css/g/g03t4bb1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wyr___g3f"/><circle class="dfv392bxj"/><path class="g03t4bb1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:server-proxy" {...props}></Icon>
