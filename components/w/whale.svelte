<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu3-06lbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nu3-06lbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:whale" {...props}></Icon>
