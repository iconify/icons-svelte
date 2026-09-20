<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsrssrbmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lsrssrbmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:wallaby" {...props}></Icon>
