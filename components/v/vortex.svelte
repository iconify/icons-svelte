<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3cn6cc3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v3cn6cc3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:vortex" {...props}></Icon>
