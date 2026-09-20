<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1so0ab6o.css';
import '../../css/p/p1-cd6b4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r1so0ab6o"/><path class="p1-cd6b4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:star-half-alt" {...props}></Icon>
