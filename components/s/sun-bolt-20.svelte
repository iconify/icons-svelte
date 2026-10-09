<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ciy5fzbxp.css';
import '../../css/a/apq2fzbyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ciy5fzbxp"/><path class="apq2fzbyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sun-bolt-20" {...props}></Icon>
