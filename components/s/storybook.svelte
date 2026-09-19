<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3e9_7b5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":420,"height":512};
const content = `<path class="h3e9_7b5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:storybook" {...props}></Icon>
