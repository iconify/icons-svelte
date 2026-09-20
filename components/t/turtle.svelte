<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmc4ovo2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="qmc4ovo2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:turtle" {...props}></Icon>
