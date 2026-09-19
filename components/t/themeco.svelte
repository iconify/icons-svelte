<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oui1n645i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="oui1n645i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:themeco" {...props}></Icon>
