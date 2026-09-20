<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-4d03kxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-4d03kxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:skip-forward-mini-line" {...props}></Icon>
