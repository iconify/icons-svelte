<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0gsqn47u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c0gsqn47u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:safe-shield-2-fill" {...props}></Icon>
