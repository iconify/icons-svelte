<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-iazk_qb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="f-iazk_qb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:springer" {...props}></Icon>
