<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8o-8jgtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p8o-8jgtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:swords-filled" {...props}></Icon>
