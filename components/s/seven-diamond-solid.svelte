<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or8qd9bvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="or8qd9bvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:seven-diamond-solid" {...props}></Icon>
