<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se3r-mb6s.css';
import '../../css/f/fecdmsb2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="se3r-mb6s"/><path class="fecdmsb2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:university-48-bold" {...props}></Icon>
