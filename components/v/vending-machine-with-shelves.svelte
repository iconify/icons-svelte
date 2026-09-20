<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy6ak9tth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gy6ak9tth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:vending-machine-with-shelves" {...props}></Icon>
