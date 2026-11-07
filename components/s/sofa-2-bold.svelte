<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6vyhu-he.css';
import '../../css/g/g_7c-1vki.css';
import '../../css/g/g97e8sbao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p6vyhu-he"/><path class="g_7c-1vki"/><path class="g97e8sbao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sofa-2-bold" {...props}></Icon>
