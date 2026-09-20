<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mx8xttprq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mx8xttprq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:weigher-bold" {...props}></Icon>
