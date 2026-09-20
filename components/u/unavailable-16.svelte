<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_nqm2quh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e_nqm2quh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:unavailable-16" {...props}></Icon>
