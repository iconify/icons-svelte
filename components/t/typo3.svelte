<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di5491bmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="di5491bmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:typo3" {...props}></Icon>
