<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxk2j9btb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wxk2j9btb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:screen-share-off" {...props}></Icon>
