<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ez5o3y60g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ez5o3y60g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:wink-square-solid" {...props}></Icon>
