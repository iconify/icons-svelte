<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swhsg8bhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="swhsg8bhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:spray" {...props}></Icon>
