<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2qxzdsyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n2qxzdsyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:sparkles-solid" {...props}></Icon>
