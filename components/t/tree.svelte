<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t44yfjbkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t44yfjbkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:tree" {...props}></Icon>
