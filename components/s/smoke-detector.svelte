<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5o7aygxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w5o7aygxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:smoke-detector" {...props}></Icon>
