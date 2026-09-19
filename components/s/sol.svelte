<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnf-kcvqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xnf-kcvqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:sol" {...props}></Icon>
