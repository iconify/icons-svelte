<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7lw6ii2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z7lw6ii2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:ruff" {...props}></Icon>
