<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj7qqac8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="oj7qqac8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:typescript" {...props}></Icon>
