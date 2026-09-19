<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhkw86bin.css';
import '../../css/x/x8cmsqbjt.css';
import '../../css/t/tx7rwubgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yhkw86bin"/><path class="x8cmsqbjt"/><path class="tx7rwubgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:study-view" {...props}></Icon>
