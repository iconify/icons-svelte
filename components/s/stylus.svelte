<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3ofrjb9b.css';
import '../../css/j/j1hjbo5ut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a3ofrjb9b"/><path class="j1hjbo5ut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:stylus" {...props}></Icon>
