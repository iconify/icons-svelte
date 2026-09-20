<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0qd9kuvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r0qd9kuvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:tooth-fill" {...props}></Icon>
