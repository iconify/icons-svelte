<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnbwfo_-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nnbwfo_-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:two-solid" {...props}></Icon>
