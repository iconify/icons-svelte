<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw8jb2bqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lw8jb2bqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wechat-dark" {...props}></Icon>
