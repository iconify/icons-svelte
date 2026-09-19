<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5nl78bqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5nl78bqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:unfold" {...props}></Icon>
