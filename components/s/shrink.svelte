<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/na-qutbrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="na-qutbrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:shrink" {...props}></Icon>
