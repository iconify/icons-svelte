<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-3pvhb7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-3pvhb7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:user-asking" {...props}></Icon>
