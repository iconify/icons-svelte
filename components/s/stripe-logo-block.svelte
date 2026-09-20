<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pg2ybx44l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pg2ybx44l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:stripe-logo-block" {...props}></Icon>
