<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6g4f8bmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p6g4f8bmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:zazzle" {...props}></Icon>
