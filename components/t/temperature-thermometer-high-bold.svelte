<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3os1xhir.css';
import '../../css/d/d6d0x4b4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3os1xhir"/><path class="d6d0x4b4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:temperature-thermometer-high-bold" {...props}></Icon>
