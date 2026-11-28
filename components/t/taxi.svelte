<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oze_5-bqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oze_5-bqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:taxi" {...props}></Icon>
