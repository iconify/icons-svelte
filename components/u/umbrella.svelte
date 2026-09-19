<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcv8-5svs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bcv8-5svs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:umbrella" {...props}></Icon>
