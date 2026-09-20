<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1di_8b1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f1di_8b1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:ux-circle" {...props}></Icon>
