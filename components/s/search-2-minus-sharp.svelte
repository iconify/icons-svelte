<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6h7q7wkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v6h7q7wkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:search-2-minus-sharp" {...props}></Icon>
