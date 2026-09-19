<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qckhk8bfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qckhk8bfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:stadia" {...props}></Icon>
