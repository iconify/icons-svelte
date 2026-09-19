<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z49es9s7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z49es9s7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-plus-light" {...props}></Icon>
