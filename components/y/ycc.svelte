<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs17gcz1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qs17gcz1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ycc" {...props}></Icon>
