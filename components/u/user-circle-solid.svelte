<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn99dp6mo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jn99dp6mo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:user-circle-solid" {...props}></Icon>
