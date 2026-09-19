<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd5-fzb7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kd5-fzb7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:start-record-filled" {...props}></Icon>
