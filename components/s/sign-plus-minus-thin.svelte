<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fun39o8tg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fun39o8tg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-plus-minus-thin" {...props}></Icon>
