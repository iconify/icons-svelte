<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb8e72srw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xb8e72srw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:uber-symbol" {...props}></Icon>
