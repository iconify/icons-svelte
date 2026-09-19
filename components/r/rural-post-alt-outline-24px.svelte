<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijthh537c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ijthh537c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:rural-post-alt-outline-24px" {...props}></Icon>
