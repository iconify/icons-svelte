<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a94572moh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a94572moh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:signal-alt-3" {...props}></Icon>
