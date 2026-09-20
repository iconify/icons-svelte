<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgyn5dtqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pgyn5dtqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:wait" {...props}></Icon>
