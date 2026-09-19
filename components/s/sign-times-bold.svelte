<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th04ddc4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="th04ddc4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-times-bold" {...props}></Icon>
