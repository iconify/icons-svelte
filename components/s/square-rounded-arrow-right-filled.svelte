<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf5piqbyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wf5piqbyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-arrow-right-filled" {...props}></Icon>
