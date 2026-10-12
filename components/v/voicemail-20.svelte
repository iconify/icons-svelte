<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl6j6835z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bl6j6835z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:voicemail-20" {...props}></Icon>
