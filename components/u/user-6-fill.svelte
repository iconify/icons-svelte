<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f80dcccun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f80dcccun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:user-6-fill" {...props}></Icon>
