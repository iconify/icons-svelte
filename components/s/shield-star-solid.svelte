<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/objv1ybmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="objv1ybmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:shield-star-solid" {...props}></Icon>
