<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/loskjgbgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="loskjgbgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:work-item-objective" {...props}></Icon>
