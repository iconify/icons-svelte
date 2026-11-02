<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od_2fdb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="od_2fdb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:virus-fill" {...props}></Icon>
