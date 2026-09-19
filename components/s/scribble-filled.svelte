<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss9cfbbbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ss9cfbbbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:scribble-filled" {...props}></Icon>
