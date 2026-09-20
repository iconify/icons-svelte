<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqroeob7g.css';
import '../../css/i/il713jb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":240,"height":47.9};
const content = `<path class="kqroeob7g"/><path class="il713jb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:subway" {...props}></Icon>
