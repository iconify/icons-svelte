<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/im2cn8bvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="im2cn8bvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:tag-horizontal-start-sharp-fill" {...props}></Icon>
