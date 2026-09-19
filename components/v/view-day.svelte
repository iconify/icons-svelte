<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f24x832-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f24x832-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:view-day" {...props}></Icon>
