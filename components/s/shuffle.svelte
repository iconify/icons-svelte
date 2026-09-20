<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zypgudbzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zypgudbzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:shuffle" {...props}></Icon>
