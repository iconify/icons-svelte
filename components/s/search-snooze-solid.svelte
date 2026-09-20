<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb0box43i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qb0box43i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:search-snooze-solid" {...props}></Icon>
