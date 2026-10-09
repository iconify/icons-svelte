<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eoo3f_wso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="eoo3f_wso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:waterfall-20-bold" {...props}></Icon>
