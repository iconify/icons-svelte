<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpoqxabql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bpoqxabql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:vsys" {...props}></Icon>
