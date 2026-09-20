<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhj-4g1kr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bhj-4g1kr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:video-cut2-filled" {...props}></Icon>
