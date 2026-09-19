<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5gdlqr6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5gdlqr6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:selection" {...props}></Icon>
