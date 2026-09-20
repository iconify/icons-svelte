<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzvjlbbpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="qzvjlbbpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:silverware" {...props}></Icon>
