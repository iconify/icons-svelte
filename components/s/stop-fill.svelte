<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjpq_osli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bjpq_osli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:stop-fill" {...props}></Icon>
