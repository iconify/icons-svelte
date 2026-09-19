<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eoeyw0blc.css';
import '../../css/h/hg2rozmww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eoeyw0blc"/><path class="hg2rozmww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:vanilla-extract" {...props}></Icon>
