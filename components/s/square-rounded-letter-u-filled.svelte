<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/li9bapbuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="li9bapbuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-letter-u-filled" {...props}></Icon>
