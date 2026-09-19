<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bn38t4bmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bn38t4bmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:v0" {...props}></Icon>
