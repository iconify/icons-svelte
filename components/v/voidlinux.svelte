<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2mdpqsee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c2mdpqsee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:voidlinux" {...props}></Icon>
