<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/v/vv1alr.css';
import '../../css/a/aznzqi.css';
import '../../css/s/so-from-36.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c vv1alr"/><path class="a0m25c aznzqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:u-turn-left" {...props}></Icon>
