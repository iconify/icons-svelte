<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdxwq8bbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qdxwq8bbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:square-rounded-outline" {...props}></Icon>
