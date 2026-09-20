<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwmndxbxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bwmndxbxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-add-2-fill" {...props}></Icon>
