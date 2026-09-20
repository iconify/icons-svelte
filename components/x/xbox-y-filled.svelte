<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spyss-1is.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="spyss-1is"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:xbox-y-filled" {...props}></Icon>
