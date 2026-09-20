<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlmrk4ths.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zlmrk4ths"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:sort-h" {...props}></Icon>
