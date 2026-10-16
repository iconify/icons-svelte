<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyo9awbxy.css';
import '../../css/i/iip25ub1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fyo9awbxy"/><path class="iip25ub1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:used-cooking-oil-48-bold" {...props}></Icon>
