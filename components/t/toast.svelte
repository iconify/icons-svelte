<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3aiegh-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="m3aiegh-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:toast" {...props}></Icon>
