<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jno6ojglm.css';
import '../../css/y/yrc3asegu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jno6ojglm"/><path class="yrc3asegu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:spillway-48-bold" {...props}></Icon>
