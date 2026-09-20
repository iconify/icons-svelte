<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1pe9xbbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h1pe9xbbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:work-item-feature" {...props}></Icon>
