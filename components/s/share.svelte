<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxri2ddjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxri2ddjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:share" {...props}></Icon>
