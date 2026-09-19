<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz00cunvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jz00cunvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:triangle-fill" {...props}></Icon>
