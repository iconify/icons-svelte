<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-51v_02i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-51v_02i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:unlink-2" {...props}></Icon>
