<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks2-_5wjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ks2-_5wjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:type-thin" {...props}></Icon>
