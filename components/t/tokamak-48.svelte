<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as2_m7byb.css';
import '../../css/f/fe3vb5b8y.css';
import '../../css/j/j6ppqza5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="as2_m7byb"/><path class="fe3vb5b8y"/><path class="j6ppqza5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tokamak-48" {...props}></Icon>
