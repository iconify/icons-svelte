<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt0xp9boc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lt0xp9boc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:typo3" {...props}></Icon>
