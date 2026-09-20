<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4ncc7bcu.css';
import '../../css/s/s5o4ji33z.css';
import '../../css/s/shoqvpbig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s4ncc7bcu"/><path class="s5o4ji33z"/><path class="shoqvpbig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:strp" {...props}></Icon>
