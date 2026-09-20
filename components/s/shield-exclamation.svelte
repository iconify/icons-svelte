<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovw7vo7fo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovw7vo7fo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:shield-exclamation" {...props}></Icon>
