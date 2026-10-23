<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9cu6mbqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9cu6mbqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:search-slash" {...props}></Icon>
