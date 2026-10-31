<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfcdb8blk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfcdb8blk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:sparkles-alt-fill-round" {...props}></Icon>
