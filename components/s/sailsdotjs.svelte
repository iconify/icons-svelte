<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg89eib5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yg89eib5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sailsdotjs" {...props}></Icon>
