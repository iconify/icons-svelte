<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm3h6bb1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pm3h6bb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:skip-back-mini-line" {...props}></Icon>
