<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jekw5_btw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jekw5_btw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:volume-2" {...props}></Icon>
