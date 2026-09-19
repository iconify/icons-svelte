<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dihsqs3sw.css';
import '../../css/o/o69vp97da.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dihsqs3sw"/><path class="o69vp97da"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:type-pattern" {...props}></Icon>
