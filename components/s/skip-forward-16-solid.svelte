<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irwkgeb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="irwkgeb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:skip-forward-16-solid" {...props}></Icon>
