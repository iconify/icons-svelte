<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3_df9_ck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y3_df9_ck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wheelchair-fill" {...props}></Icon>
