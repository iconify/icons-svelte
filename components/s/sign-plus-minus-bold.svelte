<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogta_je5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ogta_je5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-plus-minus-bold" {...props}></Icon>
