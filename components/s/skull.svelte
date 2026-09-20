<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5m6x7bob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m5m6x7bob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:skull" {...props}></Icon>
