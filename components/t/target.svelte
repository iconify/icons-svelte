<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm938g6of.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hm938g6of"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:target" {...props}></Icon>
