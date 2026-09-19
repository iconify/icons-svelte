<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3l5rcoyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="t3l5rcoyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:square-fill-line-vertical-square-fill" {...props}></Icon>
