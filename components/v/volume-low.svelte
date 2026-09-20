<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9ms0wllv.css';
import '../../css/d/dd6fl6u9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="z9ms0wllv"/><path class="dd6fl6u9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:volume-low" {...props}></Icon>
