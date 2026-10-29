<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh39n_l_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zh39n_l_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:stop" {...props}></Icon>
