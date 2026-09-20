<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdfa5hbgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bdfa5hbgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-letter-f-filled" {...props}></Icon>
