<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft4kbctzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ft4kbctzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:trophy-sharp" {...props}></Icon>
