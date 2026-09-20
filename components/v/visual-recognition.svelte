<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnym7qbrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fnym7qbrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:visual-recognition" {...props}></Icon>
