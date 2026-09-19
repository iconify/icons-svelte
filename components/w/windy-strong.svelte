<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqe1hxm4o.css';
import '../../css/s/s7rqtiajo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gqe1hxm4o"/><path class="s7rqtiajo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:windy-strong" {...props}></Icon>
