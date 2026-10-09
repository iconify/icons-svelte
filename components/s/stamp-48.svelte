<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1m2c5x5x.css';
import '../../css/z/zxs4re9vm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l1m2c5x5x"/><path class="zxs4re9vm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:stamp-48" {...props}></Icon>
