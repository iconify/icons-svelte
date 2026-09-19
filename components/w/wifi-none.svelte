<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omspa3bsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="omspa3bsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:wifi-none" {...props}></Icon>
