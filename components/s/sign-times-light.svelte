<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hza2lvbhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hza2lvbhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-times-light" {...props}></Icon>
