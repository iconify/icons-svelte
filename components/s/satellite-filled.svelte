<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn0nwnb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cn0nwnb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:satellite-filled" {...props}></Icon>
