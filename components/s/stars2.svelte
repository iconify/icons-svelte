<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb9czabem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zb9czabem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:stars2" {...props}></Icon>
