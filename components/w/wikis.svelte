<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eaw2a-pso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eaw2a-pso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:wikis" {...props}></Icon>
