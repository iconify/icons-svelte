<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az7rfoxnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="az7rfoxnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:user-plus" {...props}></Icon>
