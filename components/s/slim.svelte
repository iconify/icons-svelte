<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l25-asbjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l25-asbjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:slim" {...props}></Icon>
