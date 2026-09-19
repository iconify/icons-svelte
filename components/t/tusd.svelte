<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_m4oobel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z_m4oobel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:tusd" {...props}></Icon>
