<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_btfpb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":558,"height":770};
const content = `<path class="z_btfpb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:sleipnir" {...props}></Icon>
