<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wux24jb9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wux24jb9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:seven" {...props}></Icon>
