<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg8otqbpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="yg8otqbpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:tree" {...props}></Icon>
