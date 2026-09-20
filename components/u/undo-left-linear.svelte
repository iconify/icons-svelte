<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfd4evfpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfd4evfpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:undo-left-linear" {...props}></Icon>
