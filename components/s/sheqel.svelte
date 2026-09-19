<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulrfz11jl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1376,"height":1408};
const content = `<path class="ulrfz11jl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:sheqel" {...props}></Icon>
