<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycbvpybhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ycbvpybhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:south-west-escape-alt-line" {...props}></Icon>
