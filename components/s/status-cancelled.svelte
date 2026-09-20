<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx9__mp1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="xx9__mp1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:status-cancelled" {...props}></Icon>
