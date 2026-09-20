<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6fgm95al.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x6fgm95al"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:two-octagon-solid" {...props}></Icon>
