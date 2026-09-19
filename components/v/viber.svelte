<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s52-_viwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="s52-_viwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:viber" {...props}></Icon>
