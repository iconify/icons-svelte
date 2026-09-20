<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v74qen_bm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v74qen_bm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:tent-tree" {...props}></Icon>
