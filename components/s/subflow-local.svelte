<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu47qlb-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vu47qlb-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:subflow-local" {...props}></Icon>
