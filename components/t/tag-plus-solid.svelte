<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls8nwe1ya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ls8nwe1ya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:tag-plus-solid" {...props}></Icon>
