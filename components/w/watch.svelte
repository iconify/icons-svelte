<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae_zx42gh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ae_zx42gh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:watch" {...props}></Icon>
