<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jihn21i9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="jihn21i9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:vertical-align-top" {...props}></Icon>
