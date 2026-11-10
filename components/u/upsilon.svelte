<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muqxr2obz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="muqxr2obz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:upsilon" {...props}></Icon>
