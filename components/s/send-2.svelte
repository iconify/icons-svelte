<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh5nt7b6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eh5nt7b6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:send-2" {...props}></Icon>
