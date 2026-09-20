<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja0m9bhlu.css';
import '../../css/j/j30cpac7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ja0m9bhlu"/><path class="j30cpac7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:tig" {...props}></Icon>
