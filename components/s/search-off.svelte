<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-jk7n77c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-jk7n77c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:search-off" {...props}></Icon>
