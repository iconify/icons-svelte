<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2hyn8xrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o2hyn8xrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:slickpic" {...props}></Icon>
