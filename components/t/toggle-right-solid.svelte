<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwl_y62-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kwl_y62-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:toggle-right-solid" {...props}></Icon>
