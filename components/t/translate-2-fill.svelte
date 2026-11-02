<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lypt8ll5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lypt8ll5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:translate-2-fill" {...props}></Icon>
