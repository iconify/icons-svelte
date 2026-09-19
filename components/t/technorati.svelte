<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q__-3obnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1013};
const content = `<path class="q__-3obnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:technorati" {...props}></Icon>
