<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyhfrgbxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jyhfrgbxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sync-box" {...props}></Icon>
