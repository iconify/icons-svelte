<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8r58urgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c8r58urgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-f-bold" {...props}></Icon>
