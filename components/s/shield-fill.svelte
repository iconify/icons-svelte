<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddkj1ibij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ddkj1ibij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:shield-fill" {...props}></Icon>
