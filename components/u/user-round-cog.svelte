<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsntlkb9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vsntlkb9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:user-round-cog" {...props}></Icon>
