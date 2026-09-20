<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6fa4qrzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y6fa4qrzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:square" {...props}></Icon>
