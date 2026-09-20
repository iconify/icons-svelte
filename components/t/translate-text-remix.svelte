<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yct1-hxkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yct1-hxkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:translate-text-remix" {...props}></Icon>
