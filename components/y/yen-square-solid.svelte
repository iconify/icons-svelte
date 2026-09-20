<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqy3-uvcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dqy3-uvcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:yen-square-solid" {...props}></Icon>
