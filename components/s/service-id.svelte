<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ho8767n6t.css';
import '../../css/r/rhprpwbal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ho8767n6t"/><path class="rhprpwbal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:service-id" {...props}></Icon>
