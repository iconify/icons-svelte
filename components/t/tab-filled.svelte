<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kj8xb4akc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kj8xb4akc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:tab-filled" {...props}></Icon>
