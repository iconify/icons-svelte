<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj5grvbzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hj5grvbzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:star" {...props}></Icon>
