<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovamrv60q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ovamrv60q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:smoke" {...props}></Icon>
