<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/taq8lbfgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="taq8lbfgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:sankey-diagram-alt" {...props}></Icon>
