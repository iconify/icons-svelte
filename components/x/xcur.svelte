<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhlu70bij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jhlu70bij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:xcur" {...props}></Icon>
