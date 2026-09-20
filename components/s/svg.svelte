<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns92qbcwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ns92qbcwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:svg" {...props}></Icon>
