<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9u_4xbqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f9u_4xbqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:wheat-solid" {...props}></Icon>
