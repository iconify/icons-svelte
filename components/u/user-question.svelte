<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5fzpab0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w5fzpab0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:user-question" {...props}></Icon>
