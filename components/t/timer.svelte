<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yds4fl__v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yds4fl__v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:timer" {...props}></Icon>
