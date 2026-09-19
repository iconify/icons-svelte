<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw9k31bvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":240,"height":700};
const content = `<path class="lw9k31bvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:triangle-up" {...props}></Icon>
