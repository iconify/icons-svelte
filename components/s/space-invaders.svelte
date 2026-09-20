<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/em1zy3qkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="em1zy3qkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:space-invaders" {...props}></Icon>
