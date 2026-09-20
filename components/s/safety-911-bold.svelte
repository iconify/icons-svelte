<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp4irbc5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tp4irbc5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:safety-911-bold" {...props}></Icon>
