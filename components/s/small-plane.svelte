<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko-_e_tll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ko-_e_tll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:small-plane" {...props}></Icon>
