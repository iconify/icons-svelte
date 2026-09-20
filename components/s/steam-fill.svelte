<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5n7i0b6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5n7i0b6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:steam-fill" {...props}></Icon>
