<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqjs2qjlu.css';
import '../../css/l/lsmjwzymg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqjs2qjlu"/><path class="lsmjwzymg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:window-arrow-in-filled" {...props}></Icon>
