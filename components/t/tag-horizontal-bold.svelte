<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4ku_18or.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b4ku_18or"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:tag-horizontal-bold" {...props}></Icon>
