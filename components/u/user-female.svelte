<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-4vguraq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="c-4vguraq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:user-female" {...props}></Icon>
