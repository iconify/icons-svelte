<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7d28tslr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":650,"height":679};
const content = `<path class="i7d28tslr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:vimeo" {...props}></Icon>
