<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja2n6ac7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ja2n6ac7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:tag-free-circle" {...props}></Icon>
