<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eth0z0b8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eth0z0b8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:sparkles" {...props}></Icon>
