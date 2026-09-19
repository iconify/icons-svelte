<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqtlj-uml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hqtlj-uml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:skip-backward-fill" {...props}></Icon>
