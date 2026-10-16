<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzqmkgkzn.css';
import '../../css/b/bz4e11bbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nzqmkgkzn"/><path class="bz4e11bbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:seed-48-bold" {...props}></Icon>
