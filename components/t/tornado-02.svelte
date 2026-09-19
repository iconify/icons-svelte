<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7kj4tflr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o7kj4tflr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:tornado-02" {...props}></Icon>
