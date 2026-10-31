<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enk4_gbkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="enk4_gbkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:server-round" {...props}></Icon>
