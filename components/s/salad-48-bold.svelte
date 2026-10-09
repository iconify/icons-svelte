<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tudb-7bht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tudb-7bht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:salad-48-bold" {...props}></Icon>
