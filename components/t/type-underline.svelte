<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3kg42pzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3kg42pzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:type-underline" {...props}></Icon>
