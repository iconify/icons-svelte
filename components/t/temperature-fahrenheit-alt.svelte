<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovmg3j_6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ovmg3j_6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:temperature-fahrenheit-alt" {...props}></Icon>
