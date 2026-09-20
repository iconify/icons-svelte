<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt9ryfb5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jt9ryfb5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:tiktok-line" {...props}></Icon>
