<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku2teloen.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ku2teloen"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:whole-word-solid" {...props}></Icon>
