<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8zpm-b6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8zpm-b6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:steam-line" {...props}></Icon>
