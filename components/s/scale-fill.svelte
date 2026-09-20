<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5vg0db_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t5vg0db_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:scale-fill" {...props}></Icon>
