<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko7gq5nqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ko7gq5nqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:volume-plus" {...props}></Icon>
