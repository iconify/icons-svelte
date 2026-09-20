<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct8ahm03y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ct8ahm03y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:zoom-question-filled" {...props}></Icon>
