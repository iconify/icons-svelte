<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqg9c-b8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xqg9c-b8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:text-align-center" {...props}></Icon>
