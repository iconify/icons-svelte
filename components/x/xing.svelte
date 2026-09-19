<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuab06j5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kuab06j5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:xing" {...props}></Icon>
