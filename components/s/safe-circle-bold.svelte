<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/el80ilbsd.css';
import '../../css/s/s__natbch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="el80ilbsd"/><path clip-rule="evenodd" class="s__natbch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:safe-circle-bold" {...props}></Icon>
