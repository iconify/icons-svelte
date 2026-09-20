<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6ui85kay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6ui85kay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-plus-filled" {...props}></Icon>
