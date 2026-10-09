<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_d0rvbso.css';
import '../../css/a/ak7-_zcym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a_d0rvbso"/><path class="ak7-_zcym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:stamp-48-bold" {...props}></Icon>
