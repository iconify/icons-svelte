<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exscprmgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="exscprmgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:wallet-alt-line" {...props}></Icon>
