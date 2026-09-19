<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9ctkhbgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i9ctkhbgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:square" {...props}></Icon>
