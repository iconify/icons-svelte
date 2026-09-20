<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eln99ybja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eln99ybja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:transaction-minus" {...props}></Icon>
