<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4ll1_buo.css';
import '../../css/v/vd6phjbuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="e4ll1_buo"/><path class="vd6phjbuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:top-right" {...props}></Icon>
