<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp9nu-mfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xp9nu-mfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:source-commit-next-local" {...props}></Icon>
