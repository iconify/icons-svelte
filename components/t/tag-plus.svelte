<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bck3y324g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bck3y324g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:tag-plus" {...props}></Icon>
