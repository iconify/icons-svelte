<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah7jzxbdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ah7jzxbdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tab-find" {...props}></Icon>
