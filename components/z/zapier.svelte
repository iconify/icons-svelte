<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t12e_-gwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t12e_-gwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:zapier" {...props}></Icon>
