<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u92_avmsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u92_avmsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:rural-post-alt-24px" {...props}></Icon>
