<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua3jl-yvs.css';
import '../../css/q/q3ohsnbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ua3jl-yvs"/><path clip-rule="evenodd" class="q3ohsnbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:user-portrayal-filled" {...props}></Icon>
