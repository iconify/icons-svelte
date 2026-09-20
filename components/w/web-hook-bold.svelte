<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aom6z3bju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aom6z3bju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:web-hook-bold" {...props}></Icon>
