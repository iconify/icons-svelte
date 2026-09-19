<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb4gcfb7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nb4gcfb7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:unlock-fill" {...props}></Icon>
