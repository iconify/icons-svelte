<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1v9xgbmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1v9xgbmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-chevron-right-filled" {...props}></Icon>
