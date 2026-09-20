<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4mj43pwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e4mj43pwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-number-6-filled" {...props}></Icon>
