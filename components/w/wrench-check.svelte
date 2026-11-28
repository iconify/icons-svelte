<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq59lj-wv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wq59lj-wv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:wrench-check" {...props}></Icon>
