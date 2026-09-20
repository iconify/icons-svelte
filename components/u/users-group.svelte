<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by8miib6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="by8miib6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:users-group" {...props}></Icon>
