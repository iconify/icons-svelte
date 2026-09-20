<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yc9v22bql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yc9v22bql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:spray-paint-solid" {...props}></Icon>
