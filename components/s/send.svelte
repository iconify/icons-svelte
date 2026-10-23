<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn84l-der.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fn84l-der"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:send" {...props}></Icon>
