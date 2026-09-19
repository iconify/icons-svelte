<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo7a-ubbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bo7a-ubbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:server-stack-03" {...props}></Icon>
