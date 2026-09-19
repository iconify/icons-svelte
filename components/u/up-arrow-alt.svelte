<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjg93ebpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rjg93ebpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:up-arrow-alt" {...props}></Icon>
