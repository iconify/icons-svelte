<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv2yl7bqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kv2yl7bqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-equal-bold" {...props}></Icon>
