<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkq23losc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":669};
const content = `<path class="qkq23losc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:tabs" {...props}></Icon>
