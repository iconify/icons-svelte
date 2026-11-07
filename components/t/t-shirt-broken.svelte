<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqdio7zmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqdio7zmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:t-shirt-broken" {...props}></Icon>
